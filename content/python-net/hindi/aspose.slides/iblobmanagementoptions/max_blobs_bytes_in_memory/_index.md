---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory प्रॉपर्टी
परिभाषित करता है अधिकतम कुल आकार (बाइट्स में) जो सभी BLOBs मेमोरी में कब्जा कर सकते हैं। डिफ़ॉल्ट रूप से, सभी BLOBs
लोड हो जाते हैं; केवल जब यह सीमा पहुँचती है, तब वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) उपयोग किए जाते हैं। मेमोरी में BLOBs को रखना प्रदर्शन को अधिकतम करता है लेकिन इससे उच्च मेमोरी उपयोग हो सकता है। इस प्रॉपर्टी का उपयोग अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए करें।

### टिप्पणियाँ

यह प्रॉपर्टी तब अनदेखी की जाती है जब [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) को false पर सेट किया जाता है, क्योंकि उस समय मेमोरी ही उपलब्ध唯一 संग्रह स्थान होता है और इन-मेमोरी BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं पड़ता।

### परिभाषा:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### देखें भी
* क्लास [`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)