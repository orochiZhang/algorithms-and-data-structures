# algorithms-and-data-structures 
用python刷leetcode，系统地总结知识点。 

## 链表
1. 循环链表
2. 双向链表
3. 双向循环链表

## 栈，队列

## 字符串
1. [KMP字符串匹配](https://github.com/orochiZhang/basal-algorithms/blob/master/string/KMP.md)
2. [滑动窗口算法](https://github.com/orochiZhang/basal-algorithms/blob/master/string/Sliding_Window.md)

## 树
### 基本概念
1. 某节点所拥有子树个数称为节点度。
2. 树中各节点度最大值，称为树的度。
3. 根节点层数为1，树中所有结点最大层数称为树的深度（高度）。
### 有序树，无序树
若交换结点的各子树相对位置，构成不同的树，这是有序树，否则是无序树。
### 树的遍历
树有前序，后序，层序遍历（广度遍历，从左到右）。   
树没有中序遍历，二叉树才有中序遍历。
### 算法
1. B+树

## 二叉树
### 基本概念
二叉树是一种特殊的树形结构：二叉树中的每个结点至多有2棵子树（即每个结点的度小于等于2），并且两个子树有左右之分，顺序不可颠倒。在二叉树中还有种特殊的二叉树就是完全二叉树：所有结点中除了叶子结点以外的结点都有两棵子树。如果完全二叉树中只有最底层为叶子结点那么又称为满二叉树。
### 基本性质
1. 二叉树第i层最多有2<sup>i-1</sup>个结点。
2. 深度为k的二叉树最少有k个结点，最多有2<sup>k-1</sup>个结点。     
3. 叶子个数为N<sub>0</sub>，度为2的个数为N<sub>2</sub>，则N<sub>0</sub>=N<sub>2</sub>+1    
设N为二叉树结点总数，N<sub>1</sub>为二叉树度为1的结点数，      
那么，N=N<sub>0</sub>+N<sub>1</sub>+N<sub>2</sub>     
4. 具有n个结点完全二叉树深度为Log<sub>2</sub>n+1。
### 二叉树的遍历
1. [前序遍历](https://github.com/orochiZhang/basal-algorithms/blob/master/binary_tree/DLR.md)
2. [中序遍历](https://github.com/orochiZhang/basal-algorithms/blob/master/binary_tree/LDR.md)
3. [后序遍历](https://github.com/orochiZhang/basal-algorithms/blob/master/binary_tree/LRD.md)
4. [层序遍历](https://github.com/orochiZhang/basal-algorithms/blob/master/binary_tree/level-order-traversal.md)
### 二叉树的存储
1. 二叉树的链式存储
2. 二叉树的线性存储
### 二叉树的形态
1. 斜树  
2. 满二叉树   
3. 完全二叉树   

## 图
1. 基本概念
### 图的遍历
1. 深度优先遍历
2. 广度优先遍历
### 最小生成树


## 排序
1. 冒泡
2. 选择
3. 插入
4. 希尔
5. 桶
6. 基数
7. 快排
8. 归并
9. 堆排序

## 查找
1. [二分](https://github.com/orochiZhang/basal-algorithms/blob/master/search/binary-search.md)

## 动态规划（DP）
1. 爬楼梯
2. 挖金矿
3. 打家劫舍
