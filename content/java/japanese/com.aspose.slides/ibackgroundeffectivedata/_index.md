---
title: IBackgroundEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 有効な背景プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ibackgroundeffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

有効な背景プロパティを含む不変オブジェクトです。

--------------------

[IBackground](../../com.aspose.slides/ibackground) インターフェイスと共に使用され、継承が適用された有効な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 有効な塗りつぶし形式を返します。 |
| [getEffectFormat()](#getEffectFormat--) | 有効な効果形式を返します。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


有効な塗りつぶし形式を返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


有効な効果形式を返します。読み取り専用 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**返り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)