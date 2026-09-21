---
title: delete_row method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
निर्दिष्ट पंक्ति को हटाता है


```python
def delete_row(self, row_index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| row_index | **int** | पंक्ति को हटाने के लिए शून्य-आधारित सूचकांक। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब आप मैट्रिक्स में अंतिम एकल पंक्ति को हटाने की कोशिश करते हैं |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | यदि rowIndex शून्य से कम या RowCount के बराबर या उससे अधिक है |



### संबंधित देखें
* क्लास [`MathMatrix`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)