# Binary Tree Traversals

This project demonstrates various binary tree traversal techniques. The current implementation includes **Preorder Traversal**.

## File Description

- **`src/PreOrder.java`**: Contains the implementation of a binary tree and the **Preorder Traversal** algorithm. The traversal visits nodes in the order: **Root → Left → Right**.
- **`src/InOrder.java`**: Contains the implementation of a binary tree and the **Inorder Traversal** algorithm. The traversal visits nodes in the order: **Left → Root → Right**.
- **`src/Node.java`**: Defines the `Node` class, which represents a single node in the binary tree. Each node contains:
  - An integer `data` field to store the value of the node.
  - Two references, `left` and `right`, pointing to the left and right child nodes, respectively.

## How to Run

1. Clone the repository or download the project files.
2. Navigate to the `src` directory.
3. Compile the `*.java` file using the following command:
   ```bash
   javac <filename>.java
4. Run the program 
   ```bash
   java <ClassName>
   ```
### Example Output
For the given binary tree:

        1
       / \
      2   3
     / \    \
    4   5    6


The Preorder Traversal output will be: </br>
Preorder Traversal: </br>
1 2 4 5 3 6

The Inorder Traversal output will be: </br>
Inorder Traversal: </br>
4 2 5 1 3 6

This project was created as part of a learning exercise on binary tree traversal techniques.

## Demo

Here is a demonstration of the binary tree traversal:

![Binary Tree Traversal Demo](BINARY_TREE_VIDEO_LECTURE.mp4)

For a detailed explanation, refer to the presentation:

[Binary Tree Traversal Presentation](BINARY_TREE.pptx)

