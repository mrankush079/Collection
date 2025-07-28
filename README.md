# Java Collections Overview

## 🔍 Project Purpose  
Provide a clear demonstration and reference of Java’s Collections Framework: main interfaces, commonly used implementations, and how to use them effectively in applications.

## 📚 What You’ll Learn
- The core interfaces: `Collection`, `List`, `Set`, `Queue`, `Map`
- Common implementations: `ArrayList`, `LinkedList`, `HashSet`, `TreeSet`, `PriorityQueue`, `HashMap`, `TreeMap`
- Utility operations via `Collections` class (e.g., sorting, searching, wrapping, thread‑safety)
- Basic performance characteristics and use‑case guidelines

 
- ## 📂 Project Structure
- src/
└─ main/
├─ java/
│ └─ com.example.collections/
│ ├─ DemoList.java
│ ├─ DemoSet.java
│ ├─ DemoQueue.java
│ ├─ DemoMap.java
│ └─ UtilsDemo.java
README.md


## 🚀 Quick Start
1. Clone this repository  
2. Navigate to `src/main/java/com/example/collections`  
3. Compile & run demos:

4. Each class demonstrates basic operations like add/remove, iteration, ordering, duplicate handling.

## 📘 API Reference

- **List**: ordered, allows duplicates; e.g. `ArrayList`, `LinkedList`  
- **Set**: unique elements, no duplicates; e.g. `HashSet`, `TreeSet`, `LinkedHashSet`  
- **Queue / Deque**: FIFO or double-ended; e.g. `LinkedList`, `ArrayDeque`, `PriorityQueue`  
- **Map** (not a subtype of `Collection`): key‑value pairs; e.g. `HashMap`, `TreeMap`, `LinkedHashMap` :contentReference[oaicite:11]{index=11}

## 🧠 Utility Class: `java.util.Collections`
Provides static methods for:
- Sorting (`Collections.sort(...)`)
- Searching (`binarySearch(...)`)
- Wrapping/unmodifiable views (`Collections.unmodifiableList(...)`)
- Thread-safe wrappers (`Collections.synchronizedList(...)`) :contentReference[oaicite:12]{index=12}

## 🚥 Why Use Collections over Arrays?
- Dynamic sizing (auto grow/shrink)
- Type safety via generics (no casting)
- Rich utility operations, reusability, and interoperability :contentReference[oaicite:13]{index=13}

## 🧩 Performance Tips
Choose implementation based on use case:
- `ArrayList`: fast random access; slower inserts/removals in middle  
- `LinkedList`: fast insert/remove at ends; slower `get(index)`  
- `HashSet`/`HashMap`: average O(1) operations; unordered  
- `TreeSet`/`TreeMap`: sorted order; O(log n) time complexity

## 🧾 License
(Optional – include if relevant)
