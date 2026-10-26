---
title: ITabEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 有効なテキストのタブストッププロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/itabeffectivedata/
---
**実装されているすべてのインターフェイス:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

有効なテキストのタブストッププロパティを含む不変オブジェクト。

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

タブの位置を返します。このプロパティを設定すると、コレクション内のタブのインデックスが変更され、Enumerator が無効になる可能性があります。読み取り専用 double。

**返り値:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

タブの配置スタイルを返します。読み取り専用 [TabAlignment](../../com.aspose.slides/tabalignment)。

**返り値:**
int