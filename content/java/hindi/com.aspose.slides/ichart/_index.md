---
title: IChart
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichart/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | केवल दृश्यमान कोशिकाएँ प्लॉट की गई हैं या नहीं, निर्धारित करता है। |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | केवल दृश्यमान कोशिकाएँ प्लॉट की गई हैं या नहीं, निर्धारित करता है। |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है या सेट करता है। |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है या सेट करता है। |
| [getChartData()](#getChartData--) | एक चार्ट से संबंधित लिंक्ड या एम्बेडेड डेटा की जानकारी लौटाता है। |
| [hasTitle()](#hasTitle--) | एक चार्ट में दृश्य शीर्षक है या नहीं, निर्धारित करता है। |
| [setTitle(boolean value)](#setTitle-boolean-) | एक चार्ट में दृश्य शीर्षक है या नहीं, निर्धारित करता है। |
| [getChartTitle()](#getChartTitle--) | एक चार्ट शीर्षक लौटाता है या सेट करता है केवल पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)। |
| [hasDataTable()](#hasDataTable--) | एक चार्ट में डेटा तालिका है या नहीं, निर्धारित करता है। |
| [setDataTable(boolean value)](#setDataTable-boolean-) | एक चार्ट में डेटा तालिका है या नहीं, निर्धारित करता है। |
| [hasLegend()](#hasLegend--) | एक चार्ट में लीजेंड है या नहीं, निर्धारित करता है। |
| [setLegend(boolean value)](#setLegend-boolean-) | एक चार्ट में लीजेंड है या नहीं, निर्धारित करता है। |
| [getLegend()](#getLegend--) | एक चार्ट के लिए लीजेंड लौटाता है या सेट करता है। |
| [getChartDataTable()](#getChartDataTable--) | एक चार्ट की डेटा तालिका लौटाता है। |
| [getStyle()](#getStyle--) | चार्ट शैली लौटाता है या सेट करता है। |
| [setStyle(int value)](#setStyle-int-) | चार्ट शैली लौटाता है या सेट करता है। |
| [getType()](#getType--) | चार्ट प्रकार लौटाता है या सेट करता है। |
| [setType(int value)](#setType-int-) | चार्ट प्रकार लौटाता है या सेट करता है। |
| [getPlotArea()](#getPlotArea--) | एक चार्ट के प्लॉट क्षेत्र का प्रतिनिधित्व करता है। |
| [getRotation3D()](#getRotation3D--) | एक चार्ट का 3D घुमाव लौटाता है। |
| [getBackWall()](#getBackWall--) | एक वस्तु लौटाता है जो 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देती है। |
| [getSideWall()](#getSideWall--) | एक वस्तु लौटाता है जो 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देती है। |
| [getFloor()](#getFloor--) | एक वस्तु लौटाता है जो 3D चार्ट की फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देती है। |
| [getUserShapes()](#getUserShapes--) | चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करें। |
| [getAxes()](#getAxes--) | चार्ट अक्षों तक पहुंच प्रदान करें। |
| [validateChartLayout()](#validateChartLayout--) | चार्ट तत्वों के वास्तविक मानों की गणना करता है। |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | एक चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ, निर्धारित करता है। |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | एक चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ, निर्धारित करता है। |
| [hasRoundedCorners()](#hasRoundedCorners--) | चार्ट क्षेत्र में गोल कोने हों, निर्धारित करता है। |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | चार्ट क्षेत्र में गोल कोने हों, निर्धारित करता है। |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

केवल दृश्यमान कोशिकाएँ प्लॉट की गई हैं या नहीं, निर्धारित करता है। दोनों दृश्यमान और छिपी कोशिकाओं को प्लॉट करने के लिए False। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

केवल दृश्यमान कोशिकाएँ प्लॉट की गई हैं या नहीं, निर्धारित करता है। दोनों दृश्यमान और छिपी कोशिकाओं को प्लॉट करने के लिए False। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है या सेट करता है। पढ़ें/लिखें [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।

**वापसी:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है या सेट करता है। पढ़ें/लिखें [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

एक चार्ट से संबंधित लिंक्ड या एम्बेडेड डेटा की जानकारी लौटाता है। केवल पढ़ने योग्य [IChartData](../../com.aspose.slides/ichartdata)।

**वापसी:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

एक चार्ट में दृश्य शीर्षक है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

एक चार्ट में दृश्य शीर्षक है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

एक चार्ट शीर्षक लौटाता है या सेट करता है केवल पढ़ने योग्य [IChartTitle](../../com.aspose.slides/icharttitle)।

**वापसी:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

एक चार्ट में डेटा तालिका है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

एक चार्ट में डेटा तालिका है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

एक चार्ट में लीजेंड है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

एक चार्ट में लीजेंड है या नहीं, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

एक चार्ट के लिए लीजेंड लौटाता है या सेट करता है केवल पढ़ने योग्य [ILegend](../../com.aspose.slides/ilegend)।

**वापसी:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

एक चार्ट की डेटा तालिका लौटाता है केवल पढ़ने योग्य [IDataTable](../../com.aspose.slides/idatatable)।

**वापसी:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

चार्ट शैली लौटाता है या सेट करता है पढ़ें/लिखें [StyleType](../../com.aspose.slides/styletype)।

**वापसी:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

चार्ट शैली लौटाता है या सेट करता है पढ़ें/लिखें [StyleType](../../com.aspose.slides/styletype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

चार्ट प्रकार लौटाता है या सेट करता है पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**वापसी:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

चार्ट प्रकार लौटाता है या सेट करता है पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

एक चार्ट के प्लॉट क्षेत्र का प्रतिनिधित्व करता है केवल पढ़ने योग्य [IChartPlotArea](../../com.aspose.slides/ichartplotarea)।

**वापसी:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

एक चार्ट का 3D घुमाव लौटाता है केवल पढ़ने योग्य [IRotation3D](../../com.aspose.slides/irotation3d)।

**वापसी:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

एक वस्तु लौटाता है जो 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देती है केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

एक वस्तु लौटाता है जो 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देती है केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

एक वस्तु लौटाता है जो 3D चार्ट की फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देती है केवल पढ़ने योग्य [IChartWall](../../com.aspose.slides/ichartwall)।

**वापसी:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करें केवल पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

चार्ट अक्षों तक पहुंच प्रदान करें केवल पढ़ने योग्य [IAxesManager](../../com.aspose.slides/iaxesmanager)।

**वापसी:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थिति शामिल है जो IActualLayout इंटरफ़ेस को लागू करते हैं (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) और वास्तविक अक्ष मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)।
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

एक चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

एक चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

चार्ट क्षेत्र में गोल कोने हों, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

चार्ट क्षेत्र में गोल कोने हों, निर्धारित करता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |