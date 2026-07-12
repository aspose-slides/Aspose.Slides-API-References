---
title: ISectionCollection
second_title: Java API を介した Aspose.Slides for Android のリファレンス
description: セクションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/isectioncollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

セクションのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 特定のスライドから開始する新しいセクションを追加します。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | コレクション内の指定された位置に空のセクションを追加します。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | セクションと、そのセクションに含まれるスライドを削除します。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | セクションを削除します。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | コレクションからセクションとそのスライドを指定された位置に移動します。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | コレクションの末尾に空のセクションを追加します。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | コレクション内の指定されたセクションのインデックスを返します。 |
| [clear()](#clear--) | コレクションからすべてのセクションを削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [ISection](../../com.aspose.slides/isection).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

特定のスライドから開始する新しいセクションを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | セクションの最初のスライド |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

コレクションの指定された位置に空のセクションを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |
| index | int | 新しいセクションのインデックス。 |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

セクションと、そのセクションに含まれるスライドを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | コレクションから削除するセクション。 |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

セクションを削除します。セクションに含まれるスライドは前のセクションにマージされます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | コレクションから削除するセクション。 |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

コレクションからセクションとそのスライドを指定された位置に移動します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 移動するセクション。 |
| index | int | ターゲットインデックス。 |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

コレクションの末尾に空のセクションを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | セクションの名前 |

**戻り値:**
[ISection](../../com.aspose.slides/isection) - 追加されたセクション。
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

コレクション内の指定されたセクションのインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 検索するセクション。 |

**戻り値:**
int - セクションのインデックス、またはセクションがこのコレクションに属さない場合は -1 を返します。
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのセクションを削除します。