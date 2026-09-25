---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
从 32 位 ARGB 值创建颜色。

### 返回

从指定值创建的颜色。



```python
@staticmethod
def from_argb(argb):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb | **int** | 指定 32 位 ARGB 值（有符号或无符号）的值。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 组件值小于 0 或大于 255。 |
| **TypeError** | 参数数量或类型错误。 |


## from_argb(alpha, base_color) {#int-color}
从指定的 alpha 值和基色创建颜色。

### 返回

从指定值创建的颜色。



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alpha | **int** | alpha 组件值。有效值范围为 0 到 255。 |
| base_color | [`Color`](/slides/python-net/zh/aspose.slides/color) | 用于创建新颜色的原始颜色。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 组件值小于 0 或大于 255。 |
| **TypeError** | 参数数量或类型错误。 |


## from_argb(red, green, blue) {#int-int-int}
从指定的 red、green 和 blue 值创建不透明颜色（alpha 为 255）。

### 返回

从指定值创建的颜色。



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| red | **int** | red 组件值。有效值范围为 0 到 255。 |
| green | **int** | green 组件值。有效值范围为 0 到 255。 |
| blue | **int** | blue 组件值。有效值范围为 0 到 255。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 组件值小于 0 或大于 255。 |
| **TypeError** | 参数数量或类型错误。 |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
从四个 ARGB 组件（alpha、red、green、blue）值创建颜色。

### 返回

从指定值创建的颜色.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alpha | **int** | alpha 组件值。有效值范围为 0 到 255。 |
| red | **int** | red 组件值。有效值范围为 0 到 255。 |
| green | **int** | green 组件值。有效值范围为 0 到 255。 |
| blue | **int** | blue 组件值。有效值范围为 0 到 255。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 组件值小于 0 或大于 255。 |
| **TypeError** | 参数数量或类型错误。 |



### 另请参见
* 类 [`Color`](/slides/python-net/zh/aspose.slides/color)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)