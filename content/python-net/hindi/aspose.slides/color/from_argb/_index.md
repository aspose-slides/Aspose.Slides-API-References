---
title: from_argb method
second_title: Aspose.Slides के लिये Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
32-बिट ARGB मान से एक रंग बनाता है।

### रिटर्न मान

निर्दिष्ट मान से बना रंग।



```python
@staticmethod
def from_argb(argb):
    ...
```


| परिमाण | प्रकार | विवरण |
| :- | :- | :- |
| argb | **int** | 32-बिट ARGB मान (साइन किया हुआ या अनसाइन) निर्दिष्ट करने वाला मान। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | कोई घटक मान 0 से कम या 255 से अधिक है। |
| **TypeError** | तर्कों की संख्या या प्रकार गलत है। |


## from_argb(alpha, base_color) {#int-color}
निर्दिष्ट अल्फा मान और बेस रंग से एक रंग बनाता है।

### रिटर्न मान

निर्दिष्ट मानों से बना रंग।



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| परिमाण | प्रकार | विवरण |
| :- | :- | :- |
| alpha | **int** | अल्फा घटक मान। वैध मान 0 से 255 तक हैं। |
| base_color | [`Color`](/slides/python-net/hi/aspose.slides/color) | वह रंग जिससे नया रंग बनाया जाना है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | कोई घटक मान 0 से कम या 255 से अधिक है। |
| **TypeError** | तर्कों की संख्या या प्रकार गलत है। |


## from_argb(red, green, blue) {#int-int-int}
निर्दिष्ट लाल, हरा और नीला मानों से एक अपारदर्शी रंग (अल्फा 255) बनाता है।

### रिटर्न मान

निर्दिष्ट मानों से बना रंग।



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| परिमाण | प्रकार | विवरण |
| :- | :- | :- |
| red | **int** | लाल घटक मान। वैध मान 0 से 255 तक हैं। |
| green | **int** | हरा घटक मान। वैध मान 0 से 255 तक हैं। |
| blue | **int** | नीला घटक मान। वैध मान 0 से 255 तक हैं। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | कोई घटक मान 0 से कम या 255 से अधिक है। |
| **TypeError** | तर्कों की संख्या या प्रकार गलत है। |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
चार ARGB घटकों (अल्फा, लाल, हरा और नीला) के मानों से एक रंग बनाता है।

### रिटर्न मान

निर्दिष्ट मानों से बना रंग।



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| परिमाण | प्रकार | विवरण |
| :- | :- | :- |
| alpha | **int** | अल्फा घटक मान। वैध मान 0 से 255 तक हैं। |
| red | **int** | लाल घटक मान। वैध मान 0 से 255 तक हैं। |
| green | **int** | हरा घटक मान। वैध मान 0 से 255 तक हैं। |
| blue | **int** | नीला घटक मान। वैध मान 0 से 255 तक हैं। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **ValueError** | कोई घटक मान 0 से कम या 255 से अधिक है। |
| **TypeError** | तर्कों की संख्या या प्रकार गलत है। |



### संबंधित देखें
* क्लास [`Color`](/slides/python-net/hi/aspose.slides/color)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)