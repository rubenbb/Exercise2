# Mutex and Channel basics

### What is an atomic operation?
> *An operation where a processor can both read and write on the bus at the same time, meaning any other processor or I/O unit cannot read or write while the first operation is uncomplete.*

### What is a semaphore?
> *A semiphore is a variable that keeps track of accecible resources, as well as the access to to these.*

### What is a mutex?
> *A mutex is a flag which makes sure only one thread have access at the time, therefor protecting a resource.*

### What is the difference between a mutex and a binary semaphore?
> *A mutex makes sure only one thread who accuired a resource, can release it(have access), while semiphore, another thread can release a resource.*

### What is a critical section?
> *Critical section is a part of a program that accesses shared resource. In this section it can disrupt other processes.*

### What is the difference between race conditions and data races?
 > *A race condition is when the timing of different events will affect the result, by alternating the access to a shared memory. Data race is when there is multiple memory acceses to a shared memory location.*

### List some advantages of using message passing over lock-based synchronization primitives.
> *Tends to have more simple algorithms as well as more convenience. *

### List some advantages of using lock-based synchronization primitives over message passing.
> *Tends to have more safety, as you would need the key to do an operation*
