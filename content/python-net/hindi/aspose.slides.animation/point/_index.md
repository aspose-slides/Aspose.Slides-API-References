---
title: Point class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.animation/point/
---
## Point क्लास

एनिमेशन बिंदु का प्रतिनिधित्व करता है।

The Point प्रकार निम्नलिखित सदस्य उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.animation/point/__init__/#) | डिफ़ॉल्ट निर्माणकर्ता। |
| [`__init__(self, time, value, formula)`](/slides/python-net/hi/aspose.slides.animation/point/__init__/#float-any-str) | समय, मान और सूत्र के साथ एनिमेशन बिंदु बनाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`time`](/slides/python-net/hi/aspose.slides.animation/point/time/) | समय मान का प्रतिनिधित्व करता है.<br/>            पढ़ें/लिखें **float**. |
| [`value`](/slides/python-net/hi/aspose.slides.animation/point/value/) | बिंदु मान का प्रतिनिधित्व करता है.<br/>            केवल: bool, ColorFormat, float, int, string.<br/>            पढ़ें/लिखें **any**. |
| [`formula`](/slides/python-net/hi/aspose.slides.animation/point/formula/) | मानों के भीतर सूत्र, from, to, by गुणों को इनसे बनाया जा सकता है:<br/>            मानक अंकगणितीय ऑपरेटर: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            स्थिरांक: ‘pi’ ‘e’<br/>            शर्तीय ऑपरेटर: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            तुलनात्मक ऑपरेटर: '==', '>=', '', '!=', '!'<br/>            त्रिकोणमितीय ऑपरेटर: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            प्राकृतिक लघुगणक ‘ln()’<br/>            गुण संदर्भ (होस्ट समर्थित गुण)<br/>            <br/>            उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            पढ़ें/लिखें **str**. |

### देखें
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)