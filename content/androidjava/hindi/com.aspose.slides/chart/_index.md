---
title: Chart
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: स्लाइड पर एक ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chart/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

स्लाइड पर एक ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | चार्ट तत्वों के वास्तविक मानों की गणना करता है। |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | यह निर्धारित करता है कि केवल दृश्य कोशिकाएँ प्लॉट की गई हैं या नहीं। |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | यह निर्धारित करता है कि केवल दृश्य कोशिकाएँ प्लॉट की गई हैं या नहीं। |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | चार्ट पर खाली कोशिकाओं को प्लॉट करने के तरीके को प्राप्त या सेट करता है। |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | चार्ट पर खाली कोशिकाओं को प्लॉट करने के तरीके को प्राप्त या सेट करता है। |
| [getChartData()](#getChartData--) | चार्ट से जुड़े लिंक या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। |
| [hasTitle()](#hasTitle--) | यह निर्धारित करता है कि चार्ट में एक दृश्य शीर्षक है या नहीं। |
| [setTitle(boolean value)](#setTitle-boolean-) | यह निर्धारित करता है कि चार्ट में एक दृश्य शीर्षक है या नहीं। |
| [getChartTitle()](#getChartTitle--) | चार्ट शीर्षक को प्राप्त या सेट करता है। |
| [hasDataTable()](#hasDataTable--) | यह निर्धारित करता है कि चार्ट में एक डेटा टेबल है या नहीं। |
| [setDataTable(boolean value)](#setDataTable-boolean-) | यह निर्धारित करता है कि चार्ट में एक डेटा टेबल है या नहीं। |
| [hasLegend()](#hasLegend--) | यह निर्धारित करता है कि चार्ट में एक लेज़ेंड है या नहीं। |
| [setLegend(boolean value)](#setLegend-boolean-) | यह निर्धारित करता है कि चार्ट में एक लेज़ेंड है या नहीं। |
| [getLegend()](#getLegend--) | चार्ट के लिए एक लेज़ेंड को प्राप्त या सेट करता है। |
| [getChartDataTable()](#getChartDataTable--) | चार्ट की डेटा टेबल लौटाता है। |
| [getStyle()](#getStyle--) | चार्ट स्टाइल को प्राप्त या सेट करता है। |
| [setStyle(int value)](#setStyle-int-) | चार्ट स्टाइल को प्राप्त या सेट करता है। |
| [getType()](#getType--) | चार्ट प्रकार को प्राप्त या सेट करता है। |
| [setType(int value)](#setType-int-) | चार्ट प्रकार को प्राप्त या सेट करता है। |
| [getPlotArea()](#getPlotArea--) | चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। |
| [getRotation3D()](#getRotation3D--) | चार्ट का 3D रोटेशन लौटाता है। |
| [getBackWall()](#getBackWall--) | 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। |
| [getSideWall()](#getSideWall--) | 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। |
| [getFloor()](#getFloor--) | 3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। |
| [getTextFormat()](#getTextFormat--) | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। |
| [createThemeEffective()](#createThemeEffective--) | इस चार्ट के लिए प्रभावी थीम लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम मैनेजर लौटाता है। |
| [getUserShapes()](#getUserShapes--) | चार्ट के ऊपर खींचे जाने वाले शेप्स निर्दिष्ट करता है। |
| [getAxes()](#getAxes--) | चार्ट एक्सिसेज़ तक पहुंच प्रदान करता है। |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | चार्ट के अधिकतम मान के ऊपर डेटा लेबल्स दिखाने को निर्दिष्ट करता है। |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | चार्ट के अधिकतम मान के ऊपर डेटा लेबल्स दिखाने को निर्दिष्ट करता है। |
| [hasRoundedCorners()](#hasRoundedCorners--) | चार्ट एरिया के गोल किनारे होने को निर्दिष्ट करता है। |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | चार्ट एरिया के गोल किनारे होने को निर्दिष्ट करता है। |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थिति शामिल है जो IActualLayout इंटरफ़ेस को लागू करते हैं (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) और वास्तविक एक्सिस मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) शामिल हैं।

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

यह निर्धारित करता है कि केवल दृश्य कोशिकाएँ प्लॉट की गई हैं या नहीं। छिपी कोशिकाओं को भी प्लॉट करने के लिए false सेट करें। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

यह निर्धारित करता है कि केवल दृश्य कोशिकाएँ प्लॉट की गई हैं या नहीं। छिपी कोशिकाओं को भी प्लॉट करने के लिए false सेट करें। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

चार्ट पर खाली कोशिकाओं को प्लॉट करने के तरीके को प्राप्त या सेट करता है। **पढ़ें/लिखें [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।**

**वापसी:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

चार्ट पर खाली कोशिकाओं को प्लॉट करने के तरीके को प्राप्त या सेट करता है। **पढ़ें/लिखें [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

चार्ट से जुड़े लिंक या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। **केवल पढ़ने योग्य [IChartData](../../com.aspose.slides/ichartdata)।**

**वापसी:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

यह निर्धारित करता है कि चार्ट में एक दृश्य शीर्षक है या नहीं। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

यह निर्धारित करता है कि चार्ट में एक दृश्य शीर्षक है या नहीं। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

चार्ट शीर्षक को प्राप्त या सेट करता है। **केवल पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)।**

**वापसी:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

यह निर्धारित करता है कि चार्ट में एक डेटा टेबल है या नहीं। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

यह निर्धारित करता है कि चार्ट में एक डेटा टेबल है या नहीं। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

यह निर्धारित करता है कि चार्ट में एक लेज़ेंड है या नहीं। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

यह निर्धारित करता है कि चार्ट में एक लेज़ेंड है या नहीं। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

चार्ट के लिए एक लेज़ेंड को प्राप्त या सेट करता है। **केवल पढ़ने योग्य [ILegend](../../com.aspose.slides/ilegend)।**

**वापसी:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

चार्ट की डेटा टेबल लौटाता है। **केवल पढ़ने योग्य [IDataTable](../../com.aspose.slides/idatatable)।**

**वापसी:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

चार्ट स्टाइल को प्राप्त या सेट करता है। **पढ़ें/लिखें [StyleType](../../com.aspose.slides/styletype)।**

**वापसी:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

चार्ट स्टाइल को प्राप्त या सेट करता है। **पढ़ें/लिखें [StyleType](../../com.aspose.slides/styletype)।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

चार्ट प्रकार को प्राप्त या सेट करता है। **पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।**

**वापसी:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

चार्ट प्रकार को प्राप्त या सेट करता है। **पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। **केवल पढ़ने योग्य [IChartPlotArea](../../com.aspose.slides/ichartplotarea)।**

**वापसी:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

चार्ट का 3D रोटेशन लौटाता है। **केवल पढ़ने योग्य [IRotation3D](../../com.aspose.slides/irotation3d)।**

**वापसी:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। **केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।**

**वापसी:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। **केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।**

**वापसी:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देने वाला ऑब्जेक्ट लौटाता है। **केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।**

**वापसी:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। निम्नलिखित प्रकारों के लिए यह प्रॉपर्टी लागू नहीं होती: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)। **केवल पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।**

**वापसी:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

इस चार्ट के लिए प्रभावी थीम लौटाता है।

**वापसी:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

थीम मैनेजर लौटाता है। **केवल पढ़ने योग्य [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)।**

**वापसी:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

चार्ट के ऊपर खींचे जाने वाले शेप्स निर्दिष्ट करता है। **केवल पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।**

**वापसी:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

चार्ट एक्सिसेज़ तक पहुंच प्रदान करता है। **केवल पढ़ने योग्य [IAxesManager](../../com.aspose.slides/iaxesmanager)।**

**वापसी:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

चार्ट के अधिकतम मान के ऊपर डेटा लेबल्स दिखाने को निर्धारित करता है। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

चार्ट के अधिकतम मान के ऊपर डेटा लेबल्स दिखाने को निर्धारित करता है। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

चार्ट एरिया के गोल किनारे होने को निर्धारित करता है। **पढ़ें/लिखें बूलियन।**

**वापसी:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

चार्ट एरिया के गोल किनारे होने को निर्धारित करता है। **पढ़ें/लिखें बूलियन।**

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

चार्ट को लौटाता है। **केवल पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।**

**वापसी:**  
[IChart](../../com.aspose.slides/ichart)