---
title: Details_FileNotFoundException
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "डिस्क पर मौजूद न होने वाली फ़ाइल को एक्सेस करने के प्रयास में विफलता होने पर यह अपवाद फेंका जाता है। इस क्लास की इंस्टेंस को मैन्युअली कभी न बनाएँ। इसके बजाय FileNotFoundException क्लास का उपयोग करें। FileNotFoundException क्लास की इंस्टेंस को System::SmartPtr में कभी न रैप करें।"
type: docs
weight: 183
url: /hi/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException क्लास


डिस्क पर मौजूद न होने वाली फ़ाइल को एक्सेस करने के प्रयास में विफलता होने पर यह अपवाद फेंका जाता है। इस क्लास की इंस्टेंस को मैन्युअली कभी न बनाएँ। इसके बजाय FileNotFoundException क्लास का उपयोग करें। FileNotFoundException क्लास की इंस्टेंस को [System::SmartPtr](../../system/smartptr/) में कभी न रैप करें।

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | इस अपवाद का कारण बनने वाली फ़ाइल का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## संबंधित देखें

* क्लास [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)