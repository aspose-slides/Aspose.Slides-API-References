---
title: IProtectionManager class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iprotectionmanager/
---
## IProtectionManager क्लास

प्रेजेंटेशन पासवर्ड सुरक्षा प्रबंधन।

The IProtectionManager type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/hi/aspose.slides/iprotectionmanager/encrypt_document_properties/) | यह प्रॉपर्टी तभी सार्थक है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो।<br/>            यदि true हो तो दस्तावेज़ प्रॉपर्टी प्रेजेंटेशन फ़ाइल में एन्क्रिप्ट हो जाती है।<br/>            यदि false हो तो दस्तावेज़ प्रॉपर्टी सार्वजनिक रहती है जबकि प्रेजेंटेशन एन्क्रिप्ट किया गया है।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`is_encrypted`](/slides/python-net/hi/aspose.slides/iprotectionmanager/is_encrypted/) | यह मान लौटाता है जो दर्शाता है कि यह उदाहरण एन्क्रिप्ट किया गया है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/hi/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | यह प्रॉपर्टी तभी सार्थक है जब प्रेजेंटेशन फ़ाइल पासवर्ड से संरक्षित हो और इस फ़ाइल की दस्तावेज़ प्रॉपर्टी सार्वजनिक हों।<br/>            true का मान मतलब है कि केवल दस्तावेज़ प्रॉपर्टी एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से पासवर्ड उपयोग किए बिना लोड की जाती हैं।<br/>            false का मान मतलब है कि संपूर्ण एन्क्रिप्टेड प्रेजेंटेशन सही पासवर्ड के उपयोग से लोड होती है, केवल दस्तावेज़ प्रॉपर्टी नहीं लोड होतीं।<br/>            यदि प्रेजेंटेशन एन्क्रिप्ट नहीं है तो प्रॉपर्टी मान हमेशा false रहेगा।<br/>            यदि एन्क्रिप्टेड फ़ाइल की दस्तावेज़ प्रॉपर्टी सार्वजनिक नहीं हैं तो प्रॉपर्टी मान हमेशा false रहेगा।<br/>            यदि PresentationEx.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी मान हमेशा false रहेगा।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`is_write_protected`](/slides/python-net/hi/aspose.slides/iprotectionmanager/is_write_protected/) | यह मान लौटाता है जो दर्शाता है कि यह प्रेजेंटेशन लिखने से सुरक्षित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`encryption_password`](/slides/python-net/hi/aspose.slides/iprotectionmanager/encryption_password/) | एन्क्रिप्शन पासवर्ड लौटाता है।<br/>            केवल-पढ़ने योग्य **str**. |
| [`read_only_recommended`](/slides/python-net/hi/aspose.slides/iprotectionmanager/read_only_recommended/) | केवल-पढ़ने वाली सिफ़ारिश को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **bool**. |

## विधियाँ

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/hi/aspose.slides/iprotectionmanager/encrypt/#str) | निर्दिष्ट पासवर्ड के साथ प्रेजेंटेशन को एन्क्रिप्ट करता है। |
| [`remove_encryption(self)`](/slides/python-net/hi/aspose.slides/iprotectionmanager/remove_encryption/#) | एन्क्रिप्शन को हटाता है। |
| [`set_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/iprotectionmanager/set_write_protection/#str) | निर्दिष्ट पासवर्ड के साथ इस प्रेजेंटेशन के लिए लिखने की सुरक्षा सेट करता है। |
| [`remove_write_protection(self)`](/slides/python-net/hi/aspose.slides/iprotectionmanager/remove_write_protection/#) | इस प्रेजेंटेशन की लिखने की सुरक्षा हटाता है। |
| [`check_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/iprotectionmanager/check_write_protection/#str) | निर्धारित करता है कि क्या प्रेजेंटेशन संशोधन के लिए पासवर्ड-संरक्षित है। |

### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)