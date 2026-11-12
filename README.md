# Stack Visualizer

A simple browser-based project that visualizes how a stack works using the Last In, First Out (LIFO) principle.

## What it does

This project lets you:
- Push values onto the stack
- Pop values from the stack
- Peek at the top element
- Clear the stack
- View the current stack size and top index

## Files

- `stackvisualise.html` — main interactive webpage

## How to run

1. Open `stackvisualise.html` in any modern web browser.
2. Enter a value and click **Push** to add it to the stack.
3. Use **Pop** to remove the top item and **Peek** to check the current top value.

## Stack behavior

A stack follows LIFO logic:
- The last item added is the first one removed.
- The top of the stack is the most recently inserted element.

## Example

If you push: 10, 20, 30

Then the stack order is:
- Top -> 30
- Then 20
- Then 10

When you pop, it removes 30 first.

## Notes

This is a small educational visualization designed to help understand stack operations in data structures.
