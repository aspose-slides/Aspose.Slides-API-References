---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android via Java API 參考
description: 不可變物件，表示套用於整個形狀（包括填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/iblureffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

不可變物件，表示套用於整個形狀（包括填充）的模糊效果。所有色彩通道，包括 alpha，都會受到影響。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 取得或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 判斷是否應因模糊而擴大物件的界限。 |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

取得或設定模糊半徑。唯讀 double。

**傳回：**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

判斷是否應因模糊而擴大物件的界限。True 表示界限會被擴大，false 表示不會。唯讀 boolean。

**傳回：**
boolean