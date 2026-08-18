---
title: IPortionFormat
second_title: Aspose.Slides for Java API リファレンス
description: このクラスはテキスト部分の書式設定プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/iportionformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

このクラスはテキスト部分の書式設定プロパティを含みます。[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

このクラスは、特定の部分に対して定義されたテキスト部分書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が得られます。

継承を含む有効な書式設定パラメーター値を取得するには、[getEffective](../../com.aspose.slides/iportionformat\#getEffective) メソッドを使用し、[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) インスタンスを返す必要があります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | ブックマーク識別子を取得または設定します。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | ブックマーク識別子を取得または設定します。 |
| [getSmartTagClean()](#getSmartTagClean--) | スマートタグをクリーンにすべきかどうかを判断します。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | スマートタグをクリーンにすべきかどうかを判断します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な部分書式設定データを取得します。 |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

ブックマーク識別子を取得または設定します。読み書き String。

**戻り値:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

ブックマーク識別子を取得または設定します。読み書き String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

スマートタグをクリーンにすべきかどうかを判断します。継承は適用されません。読み書き boolean。

**戻り値:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

スマートタグをクリーンにすべきかどうかを判断します。継承は適用されません。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

継承が適用された有効な部分書式設定データを取得します。

**戻り値:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) のインスタンス。