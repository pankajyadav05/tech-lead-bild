<div align="center">
	<a target="_blank" href="https://gitforcetalent.com">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://www.gitforce.ai/images/darklogo.webp">
            <source media="(prefers-color-scheme: light)" srcset="https://www.gitforce.ai/images/darklogo.webp">
            <img alt="https://gitforcetalent.com" src="https://www.gitforce.ai/images/darklogo.webp">
        </picture>
	</a>
    <br />
    <br />
</div>

---

---

# File Change Watcher

This task requires you to implement a Node.js module that can watch for file changes (creation, modification, deletion) in an AWS S3 bucket. The module should trigger appropriate events based on the detected changes. Additionally, the solution needs to be deployed on an AWS EC2 server.

## Requirements

1. **AWS S3 Bucket Watching**:

   - Watch a specified AWS S3 bucket for object (file) changes.
   - Trigger events (`add`, `change`, `unlink`) based on S3 object changes.

2. **Event Handling**:

   - Allow registering custom event handlers for each event type.
   - Pass relevant information (file/object path, change type) to the registered event handlers.

3. **Deployment**:

   - Deploy the Node.js module on an AWS EC2 server.
   - Ensure the module is running and monitoring the specified S3 bucket.

## Evaluation Criteria

- Correctness: Ensure that the implemented solution accurately detects and handles file changes in the S3 environment.
- Code Quality: Write clean, maintainable, and modular code following best practices.
- Deployment: Successful deployment and execution of the module on an AWS EC2 server.

