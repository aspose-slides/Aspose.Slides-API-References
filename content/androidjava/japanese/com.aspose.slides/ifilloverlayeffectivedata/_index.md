---
title: IFillOverlayEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Fill Overlay 効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ifilloverlayeffectivedata/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IFillOverlayEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together.

## メソッド

| Method | Description |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | 塗りの形式。 |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. 読み取り専用 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**戻り値:**
int

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


塗りの形式。 読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)