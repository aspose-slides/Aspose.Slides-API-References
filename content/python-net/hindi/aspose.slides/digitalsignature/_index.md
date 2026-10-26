---
title: DigitalSignature class
second_title: Aspose.Slides for Python के द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/digitalsignature/
---
## DigitalSignature वर्ग

हस्ताक्षरित फ़ाइल में डिजिटल हस्ताक्षर।

DigitalSignature प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/hi/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | निर्दिष्ट प्रमाणपत्र के साथ एक नया DigitalSignature ऑब्जेक्ट बनाता है। |
| [`__init__(self, file_path, password)`](/slides/python-net/hi/aspose.slides/digitalsignature/__init__/#str-str) | निर्दिष्ट प्रमाणपत्र फाइल पथ और पासवर्ड के साथ एक नया DigitalSignature ऑब्जेक्ट बनाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`certificate`](/slides/python-net/hi/aspose.slides/digitalsignature/certificate/) | दस्तावेज़ पर हस्ताक्षर करने के लिये उपयोग किया गया Certificate ऑब्जेक्ट।<br/>            Read-only **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/hi/aspose.slides/digitalsignature/is_valid/) | यदि यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं की गई है, तो यह मान true होगा।<br/>            Read-only **bool**. |
| [`sign_time`](/slides/python-net/hi/aspose.slides/digitalsignature/sign_time/) | दस्तावेज़ पर हस्ताक्षर किए जाने का समय।<br/>            Read-only **System.DateTime**. |
| [`comments`](/slides/python-net/hi/aspose.slides/digitalsignature/comments/) | हस्ताक्षर का उद्देश्य।<br/>            Read/write **str**. |


### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)