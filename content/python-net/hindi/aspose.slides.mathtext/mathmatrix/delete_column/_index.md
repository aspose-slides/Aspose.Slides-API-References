---
title: delete_column method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
निर्दिष्ट कॉलम को हटाता है

```python
def delete_column(self, column_index):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| column_index | **int** | डिलिट करने वाले कॉलम का शून्य-आधारित सूचकांक |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब आप मैट्रिक्स में अंतिम एकल कॉलम को डिलिट करने का प्रयास करते हैं |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | यदि columnIndex शून्य से कम है या ColumnCount के बराबर या उससे अधिक है |

### संबंधित देखें
* क्लास [`MathMatrix`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)