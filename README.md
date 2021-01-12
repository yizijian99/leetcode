### 算法 `com.jsu.leetcode.algorithm`
> 题号与类对应规则：
> 
> 2 => Question2
> 
> 面试题 02.06 => InterviewQuestion0206
>
>面试题22 => InterviewQuestion22
>
> *若类名带下划线，下划线后面表示解决方案*

#### [2、两数相加](https://leetcode-cn.com/problems/add-two-numbers)
给出两个 非空 的链表用来表示两个非负的整数。其中，它们各自的位数是按照**逆序**的方式存储的，并且它们的每个节点只能存储 一位 数字。
如果，我们将这两个数相加起来，则会返回一个新的链表来表示它们的和。
您可以假设除了数字 0 之外，这两个数都不会以 0 开头。

**示例：**

```text
输入：(2 -> 4 -> 3) + (5 -> 6 -> 4)
输出：7 -> 0 -> 8
原因：342 + 465 = 807
```
#### [8、字符串转换整数（atoi）](https://leetcode-cn.com/problems/string-to-integer-atoi)

请你来实现一个 atoi 函数，使其能将字符串转换成整数。

首先，该函数会根据需要丢弃无用的开头空格字符，直到寻找到第一个非空格的字符为止。接下来的转化规则如下：
+ 如果第一个非空字符为正或者负号时，则将该符号与之后面尽可能多的连续数字字符组合起来，形成一个有符号整数。
+ 假如第一个非空字符是数字，则直接将其与之后连续的数字字符组合起来，形成一个整数。
+ 该字符串在有效的整数部分之后也可能会存在多余的字符，那么这些字符可以被忽略，它们对函数不应该造成影响。

注意：假如该字符串中的第一个非空格字符不是一个有效整数字符、字符串为空或字符串仅包含空白字符时，则你的函数不需要进行转换，即无法进行有效转换。

在任何情况下，若函数不能进行有效的转换时，请返回 0 。

**提示：**
+ 本题中的空白字符只包括空格字符`' '`。
+ 假设我们的环境只能存储 32 位大小的有符号整数，那么其数值范围为 [−231,  231 − 1]。如果数值超过这个范围，请返回  INT_MAX (231 − 1) 或 INT_MIN (−231) 。



#### [23. 合并K个排序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists)

合并 *k* 个排序链表，返回合并后的排序链表。请分析和描述算法的复杂度。

**示例：**

```text
输入:
[
  1->4->5,
  1->3->4,
  2->6
]
输出: 1->1->2->3->4->4->5->6
```



-----

#### [面试题 02.06.回文链表](https://leetcode-cn.com/problems/palindrome-linked-list-lcci)

编写一个函数，检查输入的链表是否是回文的。

**示例 1：**

```text
输入： 1->2
输出： false
```

**示例 2：**
```text
输入： 1->2->2->1
输出： true 
```

**进阶：**
你能否用 O(n) 时间复杂度和 O(1) 空间复杂度解决此题？



-----

#### [面试题22.链表中倒数第k个节点](https://leetcode-cn.com/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof)

输入一个链表，输出该链表中倒数第k个节点。为了符合大多数人的习惯，本题从1开始计数，即链表的尾节点是倒数第1个节点。例如，一个链表有6个节点，从头节点开始，它们的值依次是1、2、3、4、5、6。这个链表的倒数第3个节点是值为4的节点。

**示例：**
```text
给定一个链表: 1->2->3->4->5, 和 k = 2.
返回链表 4->5.
```



