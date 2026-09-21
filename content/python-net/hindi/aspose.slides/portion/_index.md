---
title: Portion class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/portion/
---
## Portion क्लास

टेक्स्ट पैराग्राफ़ के भीतर टेक्स्ट के एक भाग का प्रतिनिधित्व करता है।

Portion टाइप निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/portion/__init__/#) | Portion क्लास का एक नया इंस्टेंस आरंभ करता है। |
| [`__init__(self, str)`](/slides/python-net/hi/aspose.slides/portion/__init__/#str) | Portion क्लास का एक नया इंस्टेंस आरंभ करता है। |
| [`__init__(self, portion)`](/slides/python-net/hi/aspose.slides/portion/__init__/#portion) | Portion क्लास का एक नया इंस्टेंस आरंभ करता है। |

## गुण

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/hi/aspose.slides/portion/portion_format/) | वह ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट की गई फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं और जिस पर कोई विरासती लागू नहीं होती।<br/>            केवल-पढ़ने योग्य [`IPortionFormat`](/slides/python-net/hi/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/hi/aspose.slides/portion/text/) | भाग का साधारण टेक्स्ट प्राप्त करता या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`field`](/slides/python-net/hi/aspose.slides/portion/field/) | इस भाग का फ़ील्ड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IField`](/slides/python-net/hi/aspose.slides/ifield). |
| [`slide`](/slides/python-net/hi/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/portion/presentation/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/hi/aspose.slides/portion/add_field/#ifieldtype) | इस भाग को स्वचालित रूप से अपडेट होने वाले फ़ील्ड में बदलता है। |
| [`add_field(self, internal_string)`](/slides/python-net/hi/aspose.slides/portion/add_field/#str) | इस भाग को स्वचालित रूप से अपडेट होने वाले फ़ील्ड में बदलता है। |
| [`remove_field(self)`](/slides/python-net/hi/aspose.slides/portion/remove_field/#) | इस फ़ील्ड भाग को साधारण भाग में बदलता है। |
| [`get_rect(self)`](/slides/python-net/hi/aspose.slides/portion/get_rect/#) | वह आयत के कॉर्डिनेट्स प्राप्त करता है जो भाग को सीमित करता है। आयत में भाग के सभी पंक्तियाँ शामिल हैं, यहाँ तक कि खाली पंक्तियाँ भी। |
| [`get_coordinates(self)`](/slides/python-net/hi/aspose.slides/portion/get_coordinates/#) | भाग की शुरुआत के कॉर्डिनेट्स प्राप्त करता है। बिंदु का X कॉर्डिनेट भाग की पहली वर्ण से शुरू होने वाले बाएँ साइड बेयरिंग को दर्शाता है। Y कॉर्डिनेट में शीर्ष साइड बेयरिंग शामिल है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)