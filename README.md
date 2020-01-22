# Presentation: an Introduction to Concurrency in Python

skygate, January 2020


## Cool links

- David Beazley's awesome presentation on concurrency in Python:
 https://speakerd.s3.amazonaws.com/presentations/3770713233254908b259542c4361e976/Concurrent.pdf
- How GIL works:
https://docs.python.org/3/c-api/init.html#thread-state-and-the-global-interpreter-lock
- Another David Beazley's awesome presentation, this time about GIL:
 http://dabeaz.com/python/UnderstandingGIL.pdf
- An interesting article on Python web apps, explaining more about threads vs. asyncio and
CPU-bound tasks:
https://www.nathanvangheem.com/posts/2019/06/11/scaling-python-web-applications.html


## TODO

- How does GIL influence multithreading and multiprocessing?
- Lock (mutex) and other low-level tricks; what is a deadlock
- Add code samples to the readme (+ the source!)


##### If there's some time left:

- indeterminacy in concurrent computation? https://en.wikipedia.org/wiki/Indeterminacy_in_concurrent_computation
    - quantum mechanics :D
    - https://en.wikipedia.org/wiki/Nondeterministic_algorithm
- Concurrency models: the Actor Model, etc.
