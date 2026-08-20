---
title: IBlurEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變物件，表示套用於整個圖形（包括其填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/iblureffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

不可變物件，表示套用於整個圖形（包括其填充）的模糊效果。所有顏色通道，包括 alpha，皆會受到影響。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 決定因模糊而是否應擴大物件的邊界。 |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

返回或設定模糊半徑。唯讀 double。

**返回：**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

決定因模糊而是否應擴大物件的邊界。True 表示邊界會被擴大，false 表示不會。唯讀 boolean。

**返回：**
boolean