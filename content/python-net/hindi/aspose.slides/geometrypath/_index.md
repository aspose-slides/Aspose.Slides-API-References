---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometrypath/
---
## GeometryPath क्लास

GeometryShape का ज्यामिति पथ का प्रतिनिधित्व करता है

GeometryPath प्रकार निम्नलिखित सदस्य प्रदान करता है:

## कन्स्ट्रक्टर

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/geometrypath/__init__/#) | GeometryPath का उदाहरण बनाता है |

## गुण

| गुण | विवरण |
| :- | :- |
| [`path_data`](/slides/python-net/hi/aspose.slides/geometrypath/path_data/) | GeometryShape का ज्यामिति पथ को पथ खंडों की एरे के रूप में लौटाता है। |
| [`fill_mode`](/slides/python-net/hi/aspose.slides/geometrypath/fill_mode/) | फ़िल मोड सेट करता है |
| [`stroke`](/slides/python-net/hi/aspose.slides/geometrypath/stroke/) | स्ट्रोक उपस्थिति सेट करता है |

## मेथड

| मेथड | विवरण |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hi/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | पथ के अंत में लाइन जोड़ता है |
| [`line_to(self, x, y)`](/slides/python-net/hi/aspose.slides/geometrypath/line_to/#float-float) | पथ के अंत में लाइन जोड़ता है |
| [`line_to(self, point, index)`](/slides/python-net/hi/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | पथ के निर्दिष्ट स्थान पर लाइन जोड़ता है |
| [`line_to(self, x, y, index)`](/slides/python-net/hi/aspose.slides/geometrypath/line_to/#float-float-int) | पथ के निर्दिष्ट स्थान पर लाइन जोड़ता है |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hi/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | पथ के अंत में क्यूबिक बेज़ियर कर्व जोड़ता है |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hi/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | पथ के अंत में क्यूबिक बेज़ियर कर्व जोड़ता है |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hi/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर कर्व जोड़ता है |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hi/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर कर्व जोड़ता है |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hi/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | पथ के अंत में क्वाड्रेटिक बेज़ियर कर्व जोड़ता है |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hi/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | पथ के अंत में क्वाड्रेटिक बेज़ियर कर्व जोड़ता है |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hi/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर कर्व जोड़ता है |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hi/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर कर्व जोड़ता है |
| [`move_to(self, point)`](/slides/python-net/hi/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | अगले बिंदु की स्थिति सेट करता है। |
| [`move_to(self, x, y)`](/slides/python-net/hi/aspose.slides/geometrypath/move_to/#float-float) | अगले बिंदु की स्थिति सेट करता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/geometrypath/remove_at/#int) | ज्यामिति पथ के निर्दिष्ट इंडेक्स पर खंड को हटाता है। |
| [`close_figure(self)`](/slides/python-net/hi/aspose.slides/geometrypath/close_figure/#) | इस पथ के वर्तमान आकृति को बंद करता है |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hi/aspose.slides/geometrypath/arc_to/#float-float-float-float) | निर्दिष्ट आर्क को पथ में जोड़ता है। |

### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)