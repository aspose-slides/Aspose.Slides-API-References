---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory प्रॉपर्टी
परिभाषित करता है अधिकतम कुल आकार (बाइट्स में) जो सभी BLOBs मेमोरी में ले सकते हैं। डिफ़ॉल्ट रूप से, सभी BLOBs
            मेमोरी में लोड किए जाते हैं; केवल जब यह सीमा पहुँच जाती है, तब वैकल्पिक तंत्र (जैसे अस्थायी
            फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है लेकिन इससे उच्च मेमोरी उपयोग हो सकता है। उपयोग
            इस प्रॉपर्टी का अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए करें।

### टिप्पणियाँ

यह प्रॉपर्टी अनदेखी की जाती है यदि [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) को false सेट किया गया है, क्योंकि मेमोरी तब
            एकमात्र उपलब्ध संग्रह स्थान है और मेमोरी में BLOB उपयोग को सीमित करने का कोई प्रभाव नहीं होता।

### परिभाषा:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### संबंधित देखें
* क्लास [`BlobManagementOptions`](/slides/python-net/hi/aspose.slides/blobmanagementoptions)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)