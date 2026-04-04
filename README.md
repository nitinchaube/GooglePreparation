

## Repository Structure

```
GooglePreparation/
├── DSA/
│   └── ConceptProblem.ipynb      # Patterns, templates & 40+ LeetCode problems
├── Concurrency/
│   └── concurrency.ipynb         # Python threading, locks & classic concurrency problems
├── SystemDesign/
│   └── SystemDesign.ipynb        # ML/LLM system design & estimation drills
├── tracker.html                  # 30-day interactive prep tracker (open in browser)
└── README.md
```

## DSA — Patterns & Problems

Each section starts with a **pattern template** followed by progressively harder LeetCode problems. Problems frequently asked at Google are tagged with **(GOOGLE)**.

| Pattern | Key Problems |
|---|---|
| **Two Pointers** | Valid Palindrome, 3Sum (G), Container With Most Water, Best Time to Buy/Sell Stock |
| **Sliding Window** | Longest Substring Without Repeating Characters (G) |
| **Strings & Hashing** | Longest Palindromic Substring (G), Encode/Decode Strings (G), Minimum Window Substring (G), Longest Repeating Character Replacement |
| **Stacks & Monotonic Patterns** | Valid Parentheses, MinStack, Daily Temperatures (G), Next Greater Element, Largest Rectangle in Histogram |
| **Binary Search** | Binary Search, Search a 2D Matrix (G), Koko Eating Bananas (G), Min in Rotated Sorted Array |
| **Linked Lists & Fast/Slow Pointers** | Reverse Linked List, Merge Two Sorted Lists, Linked List Cycle, LRU Cache, Merge K Sorted Lists (G) |
| **Binary Trees** | Invert Tree, Max Depth, Same Tree, Level Order Traversal (G), Serialize/Deserialize Tree |
| **BST & Validation** | Validate BST (G), Kth Smallest in BST, LCA of BST, LCA of BT, Max Path Sum |
| **Graphs (BFS/DFS)** | Number of Islands (G), Clone Graph, Pacific Atlantic Water Flow, Course Schedule I & II |
| **Dijkstra & Union Find** | Network Delay Time (G), Redundant Connection (G), Connected Components, Valid Tree, Accounts Merge |
| **Heaps & Priority Queues** | Min-Heap from Scratch, Kth Largest in Stream, K Closest Points (G), Find Median from Stream, Task Scheduler (G) |
| **Tries & String Algorithms** | Implement Trie (G), Add/Search Words, Word Search II (G), Word Break, Longest Common Prefix |

## Concurrency — Python Threading & Synchronization

Covers core concurrency primitives with runnable code and classic interview problems.

| Topic | What's Covered |
|---|---|
| **Fundamentals** | Threads vs Processes, GIL, Race Conditions |
| **Locking** | `threading.Lock`, Deadlock detection & prevention (lock ordering) |
| **Data Structures** | Thread-safe Stack, Thread-safe LRU Cache |
| **Condition Variables** | `threading.Condition` — wait/notify patterns |
| **Classic Problems** | Reader-Writer Problem, Dining Philosophers |
| **Algorithms** | Parallel BFS |
| **Advanced** | Thread-safe Priority Queue with `Condition`, Thread-safe Trie (coarse-grained vs fine-grained / hand-over-hand locking) |

## System Design — ML/LLM Focus

Estimation-driven system design questions relevant to Google ML infrastructure roles.

- **GPU memory estimation** — sizing machines to serve a 70B parameter model (FP16, KV cache considerations)
- **Latency vs throughput trade-offs** — batching, model parallelism, quantization knobs for LLM serving
- **Estimation drills** — back-of-the-envelope calculations for interview readiness


## Getting Started

1. **Clone the repo**
   ```bash
   git clone <repo-url>
   cd GooglePreparation
   ```
2. **Install Jupyter** (if not already available)
   ```bash
   pip install notebook
   ```
3. **Launch notebooks**
   ```bash
   jupyter notebook
   ```
4. Navigate to any notebook and run cells interactively.

## Tech Stack

- **Python 3** — all code samples
- **Jupyter Notebook** — interactive execution and notes
- **HTML/CSS/JS** — progress tracker
