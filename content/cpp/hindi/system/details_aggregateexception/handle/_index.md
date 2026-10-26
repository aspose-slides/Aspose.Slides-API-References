---
title: Handle()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: प्रत्येक आंतरिक अपवाद पर एक हैंडलर फ़ंक्शन को बुलाता है और किसी भी बिना संभाले गए अपवाद को पुनः फेंकता है।
type: docs
weight: 66
url: /hi/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method

प्रत्येक आंतरिक अपवाद पर एक हैंडलर फ़ंक्शन को बुलाता है और किसी भी बिना संभाले गए अपवाद को पुनः फेंकता है।

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | एक फ़ंक्शन जो Exception लेता है और यदि इसे संभाला गया है तो true लौटाता है। |

## टिप्पणी

यदि सभी अपवाद संभाले गए हैं, तो मेथड सामान्य रूप से लौटता है; अन्यथा, एक नया AggregateException जो असंभाले गए अपवाद को सम्मिलित करता है, फेंका जाता है।

## देखें

* Typedef [Exception](../../exception/)
* क्लास [Func](../../func/)
* क्लास [Details_AggregateException](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)