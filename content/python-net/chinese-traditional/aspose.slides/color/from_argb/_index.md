---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
建立一個來自 32 位元 ARGB 值的顏色。

### 回傳

建立自指定值的顏色。



```python
@staticmethod
def from_argb(argb):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| argb | **int** | 指定 32 位元 ARGB 值 (有號或無號) 的值。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, base_color) {#int-color}
建立一個來自指定 alpha 值與基礎顏色的顏色。

### 回傳

建立自指定值的顏色



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| alpha | **int** | Alpha 組件的值。有效值範圍為 0 到 255。 |
| base_color | [`Color`](/slides/python-net/zh-hant/aspose.slides/color) | 用於建立新顏色的基礎顏色。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(red, green, blue) {#int-int-int}
建立一個不透明的顏色（alpha 為 255），使用指定的紅、綠、藍值。

### 回傳

建立自指定值的顏色。



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| red | **int** | Red 組件的值。有效值範圍為 0 到 255。 |
| green | **int** | Green 組件的值。有效值範圍為 0 到 255。 |
| blue | **int** | Blue 組件的值。有效值範圍為 0 到 255。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
使用四個 ARGB 組件（alpha、red、green、blue）值建立顏色。

### 回傳

建立自指定值的顏色。



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| alpha | **int** | Alpha 組件的值。有效值範圍為 0 到 255。 |
| red | **int** | Red 組件的值。有效值範圍為 0 到 255。 |
| green | **int** | Green 組件的值。有效值範圍為 0 到 255。 |
| blue | **int** | Blue 組件的值。有效值範圍為 0 到 255。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |



### 另請參閱
* 類別 [`Color`](/slides/python-net/zh-hant/aspose.slides/color)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)