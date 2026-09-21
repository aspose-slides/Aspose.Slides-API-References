---
title: Trendline class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/trendline/
---
## Trendline वर्ग

वर्ग चार्ट श्रृंखला की ट्रेंड लाइन का प्रतिनिधित्व करता है

Trendline प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/hi/aspose.slides.charts/trendline/trendline_name/) | ट्रेंडलाइन का नाम प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`trendline_type`](/slides/python-net/hi/aspose.slides.charts/trendline/trendline_type/) | ट्रेंड लाइन का प्रकार प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`TrendlineType`](/slides/python-net/hi/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/hi/aspose.slides.charts/trendline/format/) | ट्रेंड लाइन के स्वरूप का प्रतिनिधित्व करता है।<br/>            पढ़ें/लिखें [`IFormat`](/slides/python-net/hi/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/hi/aspose.slides.charts/trendline/backward/) | निर्दिष्ट करता है कि ट्रेंड लाइन श्रृंखला के डेटा से पहले कितनी श्रेणियों (या स्कैटर चार्ट पर इकाइयों) तक विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान हो सकता है।<br/>            पढ़ें/लिखें **float**. |
| [`forward`](/slides/python-net/hi/aspose.slides.charts/trendline/forward/) | निर्दिष्ट करता है कि ट्रेंडलाइन डेटा के बाद कितनी श्रेणियों (या स्कैटर चार्ट पर इकाइयों) तक विस्तारित होती है। स्कैटर और गैर-स्कैटर चार्ट पर, मान कोई भी गैर-नकारात्मक मान होना चाहिए।<br/>            पढ़ें/लिखें **float**. |
| [`intercept`](/slides/python-net/hi/aspose.slides.charts/trendline/intercept/) | निर्दिष्ट करता है वह मान जहाँ ट्रेंडलाइन y-अक्ष को पार करती है। यह गुण केवल तभी समर्थित होगा जब ट्रेंडलाइन प्रकार exp, linear, या poly हो।<br/>            पढ़ें/लिखें **float**. |
| [`display_equation`](/slides/python-net/hi/aspose.slides.charts/trendline/display_equation/) | निर्दिष्ट करता है कि ट्रेंडलाइन का समीकरण चार्ट पर प्रदर्शित किया जाए (Rsquaredvalue के समान लेबल में)।<br/>            पढ़ें/लिखें **bool**. |
| [`order`](/slides/python-net/hi/aspose.slides.charts/trendline/order/) | बहुपद ट्रेंडलाइन का क्रम निर्दिष्ट करता है। यह अन्य ट्रेंडलाइन प्रकारों के लिए अनदेखा किया जाता है। मान 2 से 6 के बीच होना चाहिए।<br/>            पढ़ें/लिखें **int**. |
| [`period`](/slides/python-net/hi/aspose.slides.charts/trendline/period/) | मूविंग एवरज ट्रेंडलाइन के लिए ट्रेंडलाइन की अवधि निर्दिष्ट करता है। यह अन्य ट्रेंडलाइन रूपांतरों के लिए अनदेखा किया जाता है। मान 2 से 255 के बीच होना चाहिए।<br/>            पढ़ें/लिखें **int**. |
| [`display_r_squared_value`](/slides/python-net/hi/aspose.slides.charts/trendline/display_r_squared_value/) | निर्दिष्ट करता है कि ट्रेंडलाइन का R-स्क्वेयर मान चार्ट पर प्रदर्शित हो (समीकरण के समान लेबल में)।<br/>            पढ़ें/लिखें **bool**. |
| [`related_legend_entry`](/slides/python-net/hi/aspose.slides.charts/trendline/related_legend_entry/) | इस ट्रेंडलाइन से संबंधित लेजेंड एंट्री का प्रतिनिधित्व करता है<br/>            केवल-पढ़ने योग्य [`ILegendEntryProperties`](/slides/python-net/hi/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/hi/aspose.slides.charts/trendline/text_frame_for_overriding/) | समृद्ध स्वरूपित टेक्स्ट रख सकता है। यदि यह गुण None नहीं है तो यह <br/>            स्वरूपित टेक्स्ट मान डेटा लेबल के स्वचालित रूप से निर्मित टेक्स्ट को ओवरराइड करता है।<br/>            डेटा लेबल का स्वचालित रूप से निर्मित टेक्स्ट वह टेक्स्ट है जिसे ShowSeriesName,<br/>            ShowValue, ... गुणों द्वारा प्रबंधित किया जाता है और इसे TextFormatManager.TextFormat गुण से स्वरूपित किया जाता है।<br/>            केवल-पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/trendline/text_format/) | टेक्स्ट स्वरूप लौटाता है।<br/>            केवल-पढ़ने योग्य [`IChartTextFormat`](/slides/python-net/hi/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/trendline/chart/) | पेरेंट चार्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/trendline/presentation/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hi/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | TextFrameForOverriding को पैरामीटर "text" के टेक्स्ट से प्रारंभ करता है।<br/>            यदि TextFrameForOverriding पहले से प्रारंभ किया गया है तो केवल उसका टेक्स्ट बदलता है। |

### संबंधित
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)