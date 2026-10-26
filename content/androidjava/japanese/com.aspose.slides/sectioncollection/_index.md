---
title: SectionCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: セクションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/sectioncollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

セクションのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 特定のスライドから開始するスライド セクションを追加します。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | コレクションの末尾に空のセクションを追加します。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | コレクションの指定位置に空のセクションを追加します。 |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | コレクション内の指定されたセクションのインデックスを返します。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | セクションとその中に含まれるスライドを削除します。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | セクションを削除します。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | セクションとそのスライドをコレクションから指定された位置へ移動します。 |
| [clear()](#clear--) | コレクションからすべてのセクションを削除します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション全体を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期 (スレッドセーフ) かどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ISection](../../com.aspose.slides/isection)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

特定のスライドから開始するスライド セクションを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | セクションの最初のスライド |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

コレクションの末尾に空のセクションを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

コレクションの指定位置に空のセクションを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |
| index | int | 新しいセクションのインデックス。 |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

コレクション内の指定されたセクションのインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 検索対象のセクション。 |

**戻り値:**
int - セクションのインデックス、またはセクションがこのコレクションに属さない場合は -1。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

セクションとその中に含まれるスライドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | コレクションから削除するセクション。 |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

セクションを削除します。セクションに含まれるスライドは前のセクションにマージされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | コレクションから削除するセクション。 |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

セクションとそのスライドをコレクションから指定された位置へ移動します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 移動するセクション。 |
| index | int | 対象インデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのセクションを削除します。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション全体を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列 |
| index | int | 対象配列のインデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期 (スレッドセーフ) かどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.