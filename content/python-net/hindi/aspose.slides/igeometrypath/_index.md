---
title: IGeometryPath class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometrypath/
---
## IGeometryPath क्लास

GeometryShape का ज्यामितीय पथ दर्शाता है

IGeometryPath प्रकार निम्न सदस्यों को उपलब्ध कराता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`path_data`](/slides/python-net/hi/aspose.slides/igeometrypath/path_data/) | GeometryShape का ज्यामितीय पथ को पथ खंडों की एक ऐरे के रूप में लौटाता है |
| [`fill_mode`](/slides/python-net/hi/aspose.slides/igeometrypath/fill_mode/) | भरण मोड सेट करता है |
| [`stroke`](/slides/python-net/hi/aspose.slides/igeometrypath/stroke/) | स्ट्रोक उपस्थिति सेट करता है |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/hi/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | पथ के अंत में रेखा जोड़ता है |
| [`line_to(self, x, y)`](/slides/python-net/hi/aspose.slides/igeometrypath/line_to/#float-float) | पथ के अंत में रेखा जोड़ता है |
| [`line_to(self, point, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है |
| [`line_to(self, x, y, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/line_to/#float-float-int) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/hi/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | पथ के अंत में क्यूबिक बीज़र वक्र जोड़ता है |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/hi/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | पथ के अंत में क्यूबिक बीज़र वक्र जोड़ता है |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़र वक्र जोड़ता है |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़र वक्र जोड़ता है |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/hi/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | पथ के अंत में क्वाड्रेटिक बीज़र वक्र जोड़ता है |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/hi/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | पथ के अंत में क्वाड्रेटिक बीज़र वक्र जोड़ता है |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बीज़र वक्र जोड़ता है |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बीज़र वक्र जोड़ता है |
| [`move_to(self, point)`](/slides/python-net/hi/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | अगले बिंदु की स्थिति सेट करता है |
| [`move_to(self, x, y)`](/slides/python-net/hi/aspose.slides/igeometrypath/move_to/#float-float) | अगले बिंदु की स्थिति सेट करता है |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/igeometrypath/remove_at/#int) | ज्यामितीय पथ के निर्दिष्ट अनुक्रमणिका पर खंड हटाता है |
| [`close_figure(self)`](/slides/python-net/hi/aspose.slides/igeometrypath/close_figure/#) | इस पथ के वर्तमान आकृति को बंद करता है |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/hi/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | निर्दिष्ट आर्क को पथ में जोड़ता है |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)