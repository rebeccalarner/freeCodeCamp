---
id: 5900f5451000cf542c510057
title: 问题472：舒适的距离II
challengeType: 5
videoUrl: ''
dashedName: problem-472-comfortable-distance-ii
---

# --description--

连续N个座位。 N人按照以下规则一个接一个地来到座位：没有人坐在另一个人旁边。第一个人选择任何座位。只要不违反规则1，每个后续人员选择离已经就座的人最远的座位。如果满足该条件的选择不止一个，则该人选择最左边的选择。请注意，由于规则1，某些座位肯定会未被占用，并且可以坐着的最大人数小于N（对于N> 1）。

以下是N = 15的可能座位安排：

我们看到，如果第一个人选择正确，15个座位最多可容纳7人。我们还可以看到第一个人有9个选择来最大化可能坐着的人数。

设f（N）是第一个人必须选择的数量，以最大化连续N个座位的占用者数量。因此，f（1）= 1，f（15）= 9，f（20）= 6，并且f（500）= 16。

此外，对于1≤N≤20，Σf（N）= 83，对于1≤N≤500，Σf（N）= 13343。

找到Σf（N）为1≤N≤1012。给出答案的最后8位数字。

# --hints--

`euler472()`应该返回73811586。

```js
assert.strictEqual(euler472(), 73811586);
```

# --seed--

## --seed-contents--

```js
function euler472() {

  return true;
}

euler472();
```

# --solutions--

```js
// solution required
```
