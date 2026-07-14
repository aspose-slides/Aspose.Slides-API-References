---
title: IChart
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड पर एक ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichart/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

स्लाइड पर एक ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | निर्धारित करता है कि केवल दृश्यमान सेल्स को प्लॉट किया जाता है या नहीं। |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | निर्धारित करता है कि केवल दृश्यमान सेल्स को प्लॉट किया जाता है या नहीं। |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | चार्ट पर खाली सेल्स को प्लॉट करने के तरीके को प्राप्त करता है या सेट करता है। |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | चार्ट पर खाली सेल्स को प्लॉट करने के तरीके को प्राप्त करता है या सेट करता है। |
| [getChartData()](#getChartData--) | चार्ट से जुड़े लिंक्ड या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। |
| [hasTitle()](#hasTitle--) | निर्धारित करता है कि चार्ट में एक दृश्यमान शीर्षक है या नहीं। |
| [setTitle(boolean value)](#setTitle-boolean-) | निर्धारित करता है कि चार्ट में एक दृश्यमान शीर्षक है या नहीं। |
| [getChartTitle()](#getChartTitle--) | चार्ट शीर्षक को प्राप्त करता है या सेट करता है केवल-पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)। |
| [hasDataTable()](#hasDataTable--) | निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं। |
| [setDataTable(boolean value)](#setDataTable-boolean-) | निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं। |
| [hasLegend()](#hasLegend--) | निर्धारित करता है कि चार्ट में लेजेंड है या नहीं। |
| [setLegend(boolean value)](#setLegend-boolean-) | निर्धारित करता है कि चार्ट में लेजेंड है या नहीं। |
| [getLegend()](#getLegend--) | चार्ट के लिए लेजेंड को प्राप्त करता है या सेट करता है। |
| [getChartDataTable()](#getChartDataTable--) | चार्ट की डेटा तालिका को लौटाता है। |
| [getStyle()](#getStyle--) | चार्ट शैली को प्राप्त करता है या सेट करता है। |
| [setStyle(int value)](#setStyle-int-) | चार्ट शैली को प्राप्त करता है या सेट करता है। |
| [getType()](#getType--) | चार्ट प्रकार को प्राप्त करता है या सेट करता है। |
| [setType(int value)](#setType-int-) | चार्ट प्रकार को प्राप्त करता है या सेट करता है। |
| [getPlotArea()](#getPlotArea--) | चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। |
| [getRotation3D()](#getRotation3D--) | चार्ट की 3D घुमाव को लौटाता है। |
| [getBackWall()](#getBackWall--) | ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है। |
| [getSideWall()](#getSideWall--) | ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है। |
| [getFloor()](#getFloor--) | ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देता है। |
| [getUserShapes()](#getUserShapes--) | चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करता है। |
| [getAxes()](#getAxes--) | चार्ट अक्षों तक पहुँच प्रदान करता है। |
| [validateChartLayout()](#validateChartLayout--) | चार्ट तत्वों के वास्तविक मानों की गणना करता है। |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | निर्धारित करता है कि चार्ट के अधिकतम के ऊपर डेटा लेबल दिखाए जाएँ। |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | निर्धारित करता है कि चार्ट के अधिकतम के ऊपर डेटा लेबल दिखाए जाएँ। |
| [hasRoundedCorners()](#hasRoundedCorners--) | निर्धारित करता है कि चार्ट क्षेत्र में गोल कोनों हों। |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | निर्धारित करता है कि चार्ट क्षेत्र में गोल कोनों हों। |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

निर्धारित करता है कि केवल दृश्यमान सेल्स को प्लॉट किया जाता है या नहीं। दोनों दृश्यमान और छुपे हुए सेल्स को प्लॉट करने के लिए False सेट करें। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

निर्धारित करता है कि केवल दृश्यमान सेल्स को प्लॉट किया जाता है या नहीं। दोनों दृश्यमान और छुपे हुए सेल्स को प्लॉट करने के लिए False सेट करें। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

चार्ट पर खाली सेल्स को प्लॉट करने के तरीके को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।

**वापसी:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

चार्ट पर खाली सेल्स को प्लॉट करने के तरीके को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

चार्ट से जुड़े लिंक्ड या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [IChartData](../../com.aspose.slides/ichartdata)।

**वापसी:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

निर्धारित करता है कि चार्ट में एक दृश्यमान शीर्षक है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

निर्धारित करता है कि चार्ट में एक दृश्यमान शीर्षक है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

चार्ट शीर्षक को प्राप्त करता है या सेट करता है केवल-पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)।

**वापसी:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

निर्धारित करता है कि चार्ट में लेजेंड है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

निर्धारित करता है कि चार्ट में लेजेंड है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

चार्ट के लिए लेजेंड को प्राप्त करता है या सेट करता है केवल-पढ़ने योग्य [ILegend](../../com.aspose.slides/ilegend)।

**वापसी:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

चार्ट की डेटा तालिका को प्राप्त करता है केवल-पढ़ने योग्य [IDataTable](../../com.aspose.slides/idatatable)।

**वापसी:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

चार्ट शैली को प्राप्त करता है या सेट करता है पढ़ने/लिखने योग्य [StyleType](../../com.aspose.slides/styletype)।

**वापसी:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

चार्ट शैली को प्राप्त करता है या सेट करता है पढ़ने/लिखने योग्य [StyleType](../../com.aspose.slides/styletype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

चार्ट प्रकार को प्राप्त करता है या सेट करता है पढ़ने/लिखने योग्य [ChartType](../../com.aspose.slides/charttype)।

**वापसी:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

चार्ट प्रकार को प्राप्त करता है या सेट करता है पढ़ने/लिखने योग्य [ChartType](../../com.aspose.slides/charttype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है केवल-पढ़ने योग्य [IChartPlotArea](../../com.aspose.slides/ichartplotarea)।

**वापसी:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

चार्ट की 3D घुमाव को लौटाता है केवल-पढ़ने योग्य [IRotation3D](../../com.aspose.slides/irotation3d)।

**वापसी:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है केवल-पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है केवल-पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

ऐसा ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देता है केवल-पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करता है केवल-पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

चार्ट अक्षों तक पहुँच प्रदान करता है केवल-पढ़ने योग्य [IAxesManager](../../com.aspose.slides/iaxesmanager)।

**वापसी:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थितियों शामिल हैं जो IActualLayout इंटरफ़ेस को लागू करते हैं (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) और वास्तविक अक्ष मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)।
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

निर्दिष्ट करता है कि चार्ट के अधिकतम के ऊपर डेटा लेबल दिखाए जाएँ। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

निर्दिष्ट करता है कि चार्ट के अधिकतम के ऊपर डेटा लेबल दिखाए जाएँ। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

निर्दिष्ट करता है कि चार्ट क्षेत्र में गोल कोनों हों। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

निर्दिष्ट करता है कि चार्ट क्षेत्र में गोल कोनों हों। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |