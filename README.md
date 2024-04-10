# Simplified Chat messenger

## Functional Requirements

The chat messenger will support the following features:

- **1-1 Chat:** Enable private messaging between two users.
- **Group Chats:** Allow multiple users to communicate in a single chat room.
- **Text Only:** Support for text-based messages.
- **Attachments (Optional):** Ability to attach files to messages.
- **Videos:** Support for sending and receiving video messages.
- **UTF-16:** Encoding for messages to support a wide range of characters.
- **Message Pagination:** Load messages in chunks to manage memory and network usage effectively.
- **Offline Viewing:** Messages should be accessible without an internet connection.
- **Presence:**
  - **Online Status Presence:** Indicate when a user is online.
  - **Message Status:** Show if a message has been read, sent, or failed.

## Non-Functional Requirements

The chat messenger will adhere to the following non-functional requirements:

- **End-to-End Encryption:** Ensure all messages are encrypted from sender to receiver to maintain privacy and security.
- **Consistency:** Maintain the order of messages as they were sent.
- **Cross-Device Synchronization:** Users should be able to access their message history across multiple devices, including Android and iPhone.
- **High Availability:** The service should be highly available.
- **Minimal Latency:** The system should have very minimal latency with specific performance targets:
  - **P95 Latency Target:** Provide the 95th percentile latency target.
  - **P99 Latency Target:** Provide the 99th percentile latency target.

### Note on Performance Targets

- **High Availability Percentage:** The desired uptime percentage should be specified here.
- **P95 Latency:** The maximum allowed latency for 95% of requests should be defined.
- **P99 Latency:** The maximum allowed latency for 99% of requests should be defined.

This document will be updated as the project requirements evolve.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

