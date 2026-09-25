---
title: from_argb method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
یک رنگ از مقدار ۳۲ بیتی ARGB ایجاد می‌کند.

### Returns

رنگ ایجاد شده از مقدار مشخص‌شده.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| argb | **int** | مقداری که مقدار ۳۲ بیتی ARGB را مشخص می‌کند (امضایی یا بدون امضا). |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | مقدار یک مؤلفه کمتر از 0 یا بزرگ‌تر از 255 است. |
| **TypeError** | تعداد یا نوع آرگومان‌ها اشتباه است. |


## from_argb(alpha, base_color) {#int-color}
یک رنگ از مقدار آلفای مشخص و رنگ پایه ایجاد می‌کند.

### Returns

رنگ ایجاد شده از مقادیر مشخص‌شده.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | مقدار مؤلفه آلفا. مقادیر معتبر از 0 تا 255 هستند. |
| base_color | [`Color`](/slides/python-net/fa/aspose.slides/color) | رنگی که رنگ جدید از آن ایجاد می‌شود. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | مقدار یک مؤلفه کمتر از 0 یا بزرگ‌تر از 255 است. |
| **TypeError** | تعداد یا نوع آرگومان‌ها اشتباه است. |


## from_argb(red, green, blue) {#int-int-int}
یک رنگ غیروبِرا (آلفا برابر 255) از مقادیر قرمز، سبز و آبی مشخص‌شده ایجاد می‌کند.

### Returns

رنگ ایجاد شده از مقادیر مشخص‌شده.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| red | **int** | مقدار مؤلفه قرمز. مقادیر معتبر از 0 تا 255 هستند. |
| green | **int** | مقدار مؤلفه سبز. مقادیر معتبر از 0 تا 255 هستند. |
| blue | **int** | مقدار مؤلفه آبی. مقادیر معتبر از 0 تا 255 هستند. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | مقدار یک مؤلفه کمتر از 0 یا بزرگ‌تر از 255 است. |
| **TypeError** | تعداد یا نوع آرگومان‌ها اشتباه است. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
یک رنگ از چهار مقدار مؤلفه ARGB (آلفا، قرمز، سبز و آبی) ایجاد می‌کند.

### Returns

رنگ ایجاد شده از مقادیر مشخص‌شده.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | مقدار مؤلفه آلفا. مقادیر معتبر از 0 تا 255 هستند. |
| red | **int** | مقدار مؤلفه قرمز. مقادیر معتبر از 0 تا 255 هستند. |
| green | **int** | مقدار مؤلفه سبز. مقادیر معتبر از 0 تا 255 هستند. |
| blue | **int** | مقدار مؤلفه آبی. مقادیر معتبر از 0 تا 255 هستند. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | مقدار یک مؤلفه کمتر از 0 یا بزرگ‌تر از 255 است. |
| **TypeError** | تعداد یا نوع آرگومان‌ها اشتباه است. |



### See Also
* کلاس [`Color`](/slides/python-net/fa/aspose.slides/color)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)