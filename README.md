# Reflection
## Understanding How It Works
![Image 1](image/image1.jpg)

The addition of println!("Octo's Komputer: hey hey!"); is executed on the main thread, immediately, before the executor starts running. It produces extra output right before the asynchronous execution begins, without affecting the async task itself. This indicates that the program doesn't jump straight into the async task; instead, there's a step that runs on the main thread first.