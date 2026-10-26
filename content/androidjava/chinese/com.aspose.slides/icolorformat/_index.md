---
title: IColorFormat
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示演示文稿中使用的颜色。
type: docs
url: /zh/com.aspose.slides/icolorformat/
---
**所有实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

表示演示文稿中使用的颜色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorType()](#getColorType--) | 获取或设置颜色定义方法。 |
| [setColorType(int value)](#setColorType-int-) | 获取或设置颜色定义方法。 |
| [getColor()](#getColor--) | 返回结果颜色（已应用所有颜色变换）。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 返回结果颜色（已应用所有颜色变换）。 |
| [getPresetColor()](#getPresetColor--) | 获取或设置颜色预设。 |
| [setPresetColor(int value)](#setPresetColor-int-) | 获取或设置颜色预设。 |
| [getSystemColor()](#getSystemColor--) | 获取或设置由系统颜色表标识的颜色。 |
| [setSystemColor(int value)](#setSystemColor-int-) | 获取或设置由系统颜色表标识的颜色。 |
| [getSchemeColor()](#getSchemeColor--) | 获取或设置由配色方案标识的颜色。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 获取或设置由配色方案标识的颜色。 |
| [getR()](#getR--) | 获取或设置颜色的红色分量。 |
| [setR(byte value)](#setR-byte-) | 获取或设置颜色的红色分量。 |
| [getG()](#getG--) | 获取或设置颜色的绿色分量。 |
| [setG(byte value)](#setG-byte-) | 获取或设置颜色的绿色分量。 |
| [getB()](#getB--) | 获取或设置颜色的蓝色分量。 |
| [setB(byte value)](#setB-byte-) | 获取或设置颜色的蓝色分量。 |
| [getFloatR()](#getFloatR--) | 获取或设置颜色的红色分量。 |
| [setFloatR(float value)](#setFloatR-float-) | 获取或设置颜色的红色分量。 |
| [getFloatG()](#getFloatG--) | 获取或设置颜色的绿色分量。 |
| [setFloatG(float value)](#setFloatG-float-) | 获取或设置颜色的绿色分量。 |
| [getFloatB()](#getFloatB--) | 获取或设置颜色的蓝色分量。 |
| [setFloatB(float value)](#setFloatB-float-) | 获取或设置颜色的蓝色分量。 |
| [getHue()](#getHue--) | 获取或设置 HSL 表示中颜色的色相分量。 |
| [setHue(float value)](#setHue-float-) | 获取或设置 HSL 表示中颜色的色相分量。 |
| [getSaturation()](#getSaturation--) | 获取或设置 HSL 表示中颜色的饱和度分量。 |
| [setSaturation(float value)](#setSaturation-float-) | 获取或设置 HSL 表示中颜色的饱和度分量。 |
| [getLuminance()](#getLuminance--) | 获取或设置 HSL 表示中颜色的亮度分量。 |
| [setLuminance(float value)](#setLuminance-float-) | 获取或设置 HSL 表示中颜色的亮度分量。 |
| [getColorTransform()](#getColorTransform--) | 返回已应用于颜色的颜色变换集合。 |
| [toString(int format)](#toString-int-) | 返回表示当前颜色格式的字符串。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 从“color”复制颜色格式。 |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

获取或设置颜色定义方法。读写 [ColorType](../../com.aspose.slides/colortype)。

**返回：**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

获取或设置颜色定义方法。读写 [ColorType](../../com.aspose.slides/colortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

返回结果颜色（已应用所有颜色变换）。设置 RGB 颜色并清除所有颜色变换。读写 java.lang.Integer。

**返回：**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

返回结果颜色（已应用所有颜色变换）。设置 RGB 颜色并清除所有颜色变换。读写 java.lang.Integer。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

获取或设置颜色预设。读写 [PresetColor](../../com.aspose.slides/presetcolor)。

**返回：**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

获取或设置颜色预设。读写 [PresetColor](../../com.aspose.slides/presetcolor)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

获取或设置由系统颜色表标识的颜色。读写 [SystemColor](../../com.aspose.slides/systemcolor)。

**返回：**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

获取或设置由系统颜色表标识的颜色。读写 [SystemColor](../../com.aspose.slides/systemcolor)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

获取或设置由配色方案标识的颜色。读写 [SchemeColor](../../com.aspose.slides/schemecolor)。

**返回：**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

获取或设置由配色方案标识的颜色。读写 [SchemeColor](../../com.aspose.slides/schemecolor)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

获取或设置颜色的红色分量。所有颜色变换均被忽略。读写 byte。

**返回：**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

获取或设置颜色的红色分量。所有颜色变换均被忽略。读写 byte。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

获取或设置颜色的绿色分量。所有颜色变换均被忽略。读写 byte。

**返回：**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

获取或设置颜色的绿色分量。所有颜色变换均被忽略。读写 byte。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

获取或设置颜色的蓝色分量。所有颜色变换均被忽略。读写 byte。

**返回：**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

获取或设置颜色的蓝色分量。所有颜色变换均被忽略。读写 byte。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

获取或设置颜色的红色分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

获取或设置颜色的红色分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

获取或设置颜色的绿色分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

获取或设置颜色的绿色分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

获取或设置颜色的蓝色分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

获取或设置颜色的蓝色分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

获取或设置 HSL 表示中颜色的色相分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

获取或设置 HSL 表示中颜色的色相分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

获取或设置 HSL 表示中颜色的饱和度分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

获取或设置 HSL 表示中颜色的饱和度分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

获取或设置 HSL 表示中颜色的亮度分量。所有颜色变换均被忽略。读写 float。

**返回：**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

获取或设置 HSL 表示中颜色的亮度分量。所有颜色变换均被忽略。读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

返回已应用于颜色的颜色变换集合。只读 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**返回：**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

返回表示当前颜色格式的字符串。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | int | 颜色字符串格式的类型。 |

**返回：**
java.lang.String - 表示当前颜色格式的字符串。
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

从“color”复制颜色格式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | 颜色 [IColorFormat](../../com.aspose.slides/icolorformat) |