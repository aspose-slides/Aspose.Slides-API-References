---
title: LayoutSlideHeaderFooterManager class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager क्लास

लेआउट स्लाइड फ़ूटर, तारीख-समय, पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को रखने वाला प्रबंधक दर्शाता है।  
चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं।  
निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**विरासत:**[`LayoutSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseheaderfootermanager)

LayoutSlideHeaderFooterManager प्रकार निम्नलिखित सदस्यों को प्रकट करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/is_footer_visible/) | एक फ़ूटर प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है।<br/>            Read **bool**. |
| [`is_slide_number_visible`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/is_slide_number_visible/) | एक पृष्ठ संख्या प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है.<br/>            Read**bool**. |
| [`is_date_time_visible`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/is_date_time_visible/) | एक तारीख-समय प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है.<br/>            Read**bool**. |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_footer_visibility/#bool) | स्लाइड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_slide_number_visibility/#bool) | स्लाइड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_date_time_visibility/#bool) | स्लाइड तारीख-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_footer_text(self, text)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_footer_text/#str) | स्लाइड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [`set_date_time_text(self, text)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_date_time_text/#str) | स्लाइड तारीख-समय प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है.<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं.<br/>            निर्भर स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | लेआउट स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है.<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं.<br/>            निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | लेआउट स्लाइड तारीख-समय प्लेसहोल्डर और सभी चाइल्ड तारीख-समय प्लेसहोल्डर की दृश्यता बदलता है.<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं.<br/>            निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_text/#str) | लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहॉल्डर में टेक्स्ट सेट करता है.<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं.<br/>            निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | लेआउट स्लाइड तारीख-समय प्लेसहोल्डर और सभी चाइल्ड तारीख-समय प्लेसहॉल्डर में टेक्स्ट सेट करता है.<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स पर सम्मिलित होते हैं.<br/>            निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |

### देखें
* क्लास [`BaseHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseheaderfootermanager)
* क्लास [`BaseSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseslideheaderfootermanager)
* क्लास [`LayoutSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/layoutslideheaderfootermanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)