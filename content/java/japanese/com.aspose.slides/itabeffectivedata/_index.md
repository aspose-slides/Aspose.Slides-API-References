---
title: ITabEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 実効テキストのタブ停止プロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/itabeffectivedata/
---
**実装されたすべてのインターフェイス:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

実効テキストのタブ停止プロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPosition()](#getPosition--) | タブの位置を返します。 |
| [getAlignment()](#getAlignment--) | タブの配置スタイルを返します。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


タブの位置を返します。 このプロパティを設定すると、コレクション内のタブのインデックスが変更され、Enumerator が無効になる可能性があります。 読み取り専用の double。

**戻り値:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


タブの配置スタイルを返します。 読み取り専用 [TabAlignment](../../com.aspose.slides/tabalignment)。

**戻り値:**
int