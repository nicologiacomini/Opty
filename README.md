# Opty
In this project we implemented optimistic concurrency control with backward validation.
This project is a benchmark system that allows to define the number of clients in the system, the number of entity on which do the requests, the number of write and read operations, and the duration of the execution.

## Execution
For the execution you can use the following command:
```command
opty:start(5, 10, 2, 2, 10).
```
where the parameters are respectively the follwing:
- Number of clients
- Number of entities
- Number of read operations
- Number of write operations
- Duration in seconds
