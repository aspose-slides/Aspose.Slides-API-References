---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iportion/
---
## IPortion क्लास

टेक्स्ट पैराग्राफ़ के भीतर टेक्स्ट का एक भाग दर्शाता है।

IPortion टाइप निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/hi/aspose.slides/iportion/portion_format/) | फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट पोर्शन की स्पष्ट रूप से सेट की गई फ़ॉर्मेटिंग प्रॉपर्टीज़ शामिल होती हैं और कोई विरासत लागू नहीं की गई है।<br/>            केवल-पढ़ने योग्य [`IPortionFormat`](/slides/python-net/hi/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/hi/aspose.slides/iportion/text/) | किसी पोर्शन का सादा टेक्स्ट प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`field`](/slides/python-net/hi/aspose.slides/iportion/field/) | इस पोर्शन का फ़ील्ड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IField`](/slides/python-net/hi/aspose.slides/ifield). |
| [`slide`](/slides/python-net/hi/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/iportion/presentation/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/hi/aspose.slides/iportion/add_field/#ifieldtype) | इस पोर्शन को स्वतः अपडेट होने वाले फ़ील्ड में परिवर्तित करता है। |
| [`add_field(self, internal_string)`](/slides/python-net/hi/aspose.slides/iportion/add_field/#str) | इस पोर्शन को स्वतः अपडेट होने वाले फ़ील्ड में परिवर्तित करता है। |
| [`remove_field(self)`](/slides/python-net/hi/aspose.slides/iportion/remove_field/#) | इस फ़ील्ड पोर्शन को साधारण पोर्शन में परिवर्तित करता है। |
| [`get_rect(self)`](/slides/python-net/hi/aspose.slides/iportion/get_rect/#) | पोर्शन को बाउंड करने वाले आयत के निर्देशांक प्राप्त करें। आयत में पोर्शन के सभी टेक्स्ट लाइनों को शामिल किया गया है, जिसमें खाली लाइनों भी शामिल हैं। |
| [`get_coordinates(self)`](/slides/python-net/hi/aspose.slides/iportion/get_coordinates/#) | पोर्शन की शुरुआत के निर्देशांक प्राप्त करें। बिंदु का X निर्देशांक पोर्शन की शुरुआत को दर्शाता है, जो पहले वर्ण से बाएँ साइड बियरिंग सहित है। Y निर्देशांक में शीर्ष साइड बियरिंग शामिल है। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)