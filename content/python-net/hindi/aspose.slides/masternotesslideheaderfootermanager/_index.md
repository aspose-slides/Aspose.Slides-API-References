---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager क्लास

Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders.
            Child placeholders mean placeholders are contained on depending notes slides.
            Depending notes slides use and depend on master notes slide.

**विरासत:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseheaderfootermanager)

The MasterNotesSlideHeaderFooterManager type exposes the following members:

## गुण

| संपत्ति | विवरण |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | एक फ़ूटर प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है।<br/>            Read **bool**. |
| [`is_slide_number_visible`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | एक पृष्ठ संख्या प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है।<br/>            Read**bool**. |
| [`is_date_time_visible`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | एक तिथि-समय प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है।<br/>            Read**bool**. |
| [`is_header_visible`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | एक हेडर प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है।<br/>            Read **bool**. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | स्लाइड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | स्लाइड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | स्लाइड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_footer_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | स्लाइड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [`set_date_time_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | स्लाइड तिथि-समय प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| [`set_header_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | स्लाइड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर की दृश्यता बदलता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मैास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | मास्टर स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | मास्टर स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | मास्टर स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर में टेक्स्ट सेट करता है।<br/>            चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं।<br/>            निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं। |

### देखें
* क्लास [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/basehandoutnotesslideheaderfootermanager)
* क्लास [`BaseHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseheaderfootermanager)
* क्लास [`BaseSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/baseslideheaderfootermanager)
* क्लास [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/masternotesslideheaderfootermanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)