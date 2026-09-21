---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/protectionmanager/
---
## ProtectionManager वर्ग

प्रेजेंटेशन पासवर्ड संरक्षण प्रबंधन।

The ProtectionManager type निम्नलिखित सदस्य उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/hi/aspose.slides/protectionmanager/encrypt_document_properties/) | यह प्रॉपर्टी तब मायने रखती है जब प्रेजेंटेशन पासवर्ड से संरक्षित हो।<br/>यदि true हो तो दस्तावेज़ प्रॉपर्टी प्रेजेंटेशन फ़ाइल में एन्क्रिप्टेड होती है।<br/>यदि false हो तो दस्तावेज़ प्रॉपर्टी सार्वजनिक होती है जबकि प्रेजेंटेशन एन्क्रिप्टेड रहता है।<br/>Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/hi/aspose.slides/protectionmanager/is_encrypted/) | यह दर्शाता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं।<br/>Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/hi/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | यह प्रॉपर्टी तब मायने रखती है जब प्रेजेंटेशन फ़ाइल पासवर्ड से संरक्षित हो और इस फ़ाइल की दस्तावेज़ प्रॉपर्टी सार्वजनिक हों।<br/>true का मान दर्शाता है कि केवल दस्तावेज़ प्रॉपर्टी एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से पासवर्ड के बिना लोड की जाती है।<br/>false का मान दर्शाता है कि पूरी एन्क्रिप्टेड प्रेजेंटेशन सही पासवर्ड के उपयोग से लोड होती है, न कि केवल दस्तावेज़ प्रॉपर्टी।<br/>यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी का मान हमेशा false रहेगा।<br/>यदि एन्क्रिप्टेड फ़ाइल की दस्तावेज़ प्रॉपर्टी सार्वजनिक नहीं हैं तो प्रॉपर्टी का मान हमेशा false रहेगा।<br/>यदि Presentation.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी का मान हमेशा false रहेगा।<br/>Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/hi/aspose.slides/protectionmanager/is_write_protected/) | यह दर्शाता है कि यह प्रेजेंटेशन लिखने से संरक्षित है या नहीं।<br/>Read-only **bool**. |
| [`encryption_password`](/slides/python-net/hi/aspose.slides/protectionmanager/encryption_password/) | प्रेजेंटेशन एन्क्रिप्शन के लिए उपयोग किया गया पासवर्ड प्राप्त करता है।<br/>Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/hi/aspose.slides/protectionmanager/read_only_recommended/) | पढ़ने-केवल सिफ़ारिश प्राप्त करता या सेट करता है।<br/>Read/write **bool**. |

## विधियां

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/hi/aspose.slides/protectionmanager/encrypt/#str) | निर्दिष्ट पासवर्ड के साथ प्रेज़ेंटेशन को एन्क्रिप्ट करता है। |
| [`remove_encryption(self)`](/slides/python-net/hi/aspose.slides/protectionmanager/remove_encryption/#) | एन्क्रिप्शन को हटाता है। |
| [`set_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/protectionmanager/set_write_protection/#str) | निर्दिष्ट पासवर्ड के साथ इस प्रेज़ेंटेशन के लिए लिखने की सुरक्षा सेट करता है। |
| [`remove_write_protection(self)`](/slides/python-net/hi/aspose.slides/protectionmanager/remove_write_protection/#) | इस प्रेज़ेंटेशन की लिखने की सुरक्षा हटाता है। |
| [`check_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/protectionmanager/check_write_protection/#str) | निर्धारित करता है कि कोई प्रेज़ेंटेशन संशोधित करने के लिए पासवर्ड संरक्षित है या नहीं। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)