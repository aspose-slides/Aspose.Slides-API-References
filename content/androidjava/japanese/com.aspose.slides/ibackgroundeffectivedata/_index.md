---
title: IBackgroundEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 実効的な背景プロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/ibackgroundeffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

実効的な背景プロパティを含む不変オブジェクト。

--------------------

このインターフェイスは、[IBackground](../../com.aspose.slides/ibackground) インターフェイスと組み合わせて使用され、継承が適用された実効的な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 実効的な塗りつぶし形式を返します。 |
| [getEffectFormat()](#getEffectFormat--) | 実効的な効果形式を返します。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

実効的な塗りつぶし形式を返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

実効的な効果形式を返します。読み取り専用 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**戻り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)