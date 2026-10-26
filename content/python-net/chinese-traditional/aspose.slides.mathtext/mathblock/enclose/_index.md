---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
將數學元素用括號包起來

### 回傳值

類型為 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter) 的數學元素，包含括號



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
將此區塊的子元素以指定字元（例如括號或其他字元）作為框架包起來

### 回傳值

類型為 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter) 的數學元素，包含指定的字元作為框架



```python
def enclose(self, beginning_character, ending_character):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| beginning_character | **char** | 起始字元（通常為左括號） |
| ending_character | **char** | 結束字元（通常為右括號） |

## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
將此區塊的子元素以指定字元（例如括號或其他字元）作為框架包起來，並以分隔字元作為分隔符

### 回傳值

類型為 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter) 的數學元素，包含指定的字元作為框架和分隔符



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| beginning_character | **char** | 起始字元（通常為左括號） |
| ending_character | **char** | 結束字元（通常為右括號） |
| separator_character | **char** | 分隔字元 |

### 另請參閱
* 類別 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter)
* 類別 [`MathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)