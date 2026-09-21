---
title: BulletFormat class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/bulletformat/
---
## BulletFormat वर्ग

पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।

**विरासत:**[`BulletFormat`](/slides/python-net/hi/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)

BulletFormat प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`type`](/slides/python-net/hi/aspose.slides/bulletformat/type/) | किसी पैराग्राफ के लिए बिना विरासत के बुलेट प्रकार को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`BulletType`](/slides/python-net/hi/aspose.slides/bullettype). |
| [`char`](/slides/python-net/hi/aspose.slides/bulletformat/char/) | किसी पैराग्राफ के लिए बिना विरासत के बुलेट अक्षर को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **System.Char**. |
| [`font`](/slides/python-net/hi/aspose.slides/bulletformat/font/) | किसी पैराग्राफ के लिए बिना विरासत के बुलेट फ़ॉन्ट को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IFontData`](/slides/python-net/hi/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/hi/aspose.slides/bulletformat/height/) | किसी पैराग्राफ के लिए बिना विरासत के बुलेट ऊँचाई को लौटाता या सेट करता है।<br/>            मान float.NaN निर्धारित करता है कि बुलेट पैराग्राफ के पहले भाग से ऊँचाई विरासत में लेता है।<br/>            पढ़ें/लिखें **float**. |
| [`color`](/slides/python-net/hi/aspose.slides/bulletformat/color/) | किसी पैराग्राफ के लिए बिना विरासत के बुलेट के रंग स्वरूप को लौटाता है।<br/>            केवल-पढ़ें [`IColorFormat`](/slides/python-net/hi/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/hi/aspose.slides/bulletformat/numbered_bullet_start_with/) | बिना विरासत के क्रमांकित बुलेटों के समूह के लिए प्रयुक्त पहला नंबर को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`numbered_bullet_style`](/slides/python-net/hi/aspose.slides/bulletformat/numbered_bullet_style/) | बिना विरासत के क्रमांकित बुलेट की शैली को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`NumberedBulletStyle`](/slides/python-net/hi/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/hi/aspose.slides/bulletformat/is_bullet_hard_color/) | निर्धारित करता है कि बुलेट का अपना रंग है या वह पैराग्राफ के पहले भाग से विरासत में लेता है।<br/>            **NullableBool.True**  यदि बुलेट का अपना रंग है और **NullableBool.False**  यदि बुलेट पैराग्राफ के पहले भाग से रंग विरासत में लेता है।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/hi/aspose.slides/bulletformat/is_bullet_hard_font/) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या वह पैराग्राफ के पहले भाग से विरासत में लेता है।<br/>            **NullableBool.True**  यदि बुलेट का अपना फ़ॉन्ट है और **NullableBool.False**  यदि बुलेट पैराग्राफ के पहले भाग से फ़ॉन्ट विरासत में लेता है।<br/>            पढ़ें/लिखें [`NullableBool`](/slides/python-net/hi/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/hi/aspose.slides/bulletformat/picture/) | बिना विरासत के पैराग्राफ में बुलेट के रूप में प्रयुक्त चित्र को लौटाता है।<br/>            केवल-पढ़ें [`ISlidesPicture`](/slides/python-net/hi/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/hi/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/bulletformat/presentation/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/hi/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | जब बुलेट सक्षम होते हैं तो प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है (जैसे PowerPoint पैराग्राफ बुलेट/नंबरिंग को सक्षम करता है)। यदि बुलेट निष्क्रिय हैं तो केवल पैराग्राफ Indent और MarginLeft को रीसेट करता है (जैसे PowerPoint पैराग्राफ बुलेट/नंबरिंग को निष्क्रिय करता है)। इंडेंट शिफ्ट वर्तमान बुलेट संदर्भ - IBulletFormat.Type, .NumberedBulletStyle और पहले भाग की FontHeight - के आधार पर लागू होते हैं। गैर-शून्य इंडेंट शिफ्ट वर्तमान पैराग्राफ के प्रभावी Indent और MarginLeft पर लागू होते हैं (परिणाम मान स्थानीय मान बन जाते हैं)। |
| [`get_effective(self)`](/slides/python-net/hi/aspose.slides/bulletformat/get_effective/#) | विरासत लागू होने के साथ प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### देखें भी
* वर्ग [`BulletFormat`](/slides/python-net/hi/aspose.slides/bulletformat)
* वर्ग [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* पुस्तकालय [`Aspose.Slides`](/slides/python-net)