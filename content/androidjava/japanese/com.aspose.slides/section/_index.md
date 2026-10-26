---
title: Section
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライドのセクションを表します。
type: docs
url: /ja/com.aspose.slides/section/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISection](../../com.aspose.slides/isection)  
```
public class Section extends DomObject<SectionCollection> implements ISection
```

スライドのセクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | セクションの名前。 |
| [setName(String value)](#setName-java.lang.String-) | セクションの名前。 |
| [getSectionId()](#getSectionId--) | セクション ID。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | セクションの最初のスライドを返します。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | セクション内のスライドのリストを返します。 |

### getName() {#getName--}
```
public final String getName()
```

セクションの名前です。

**戻り値:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

セクションの名前です。

**パラメーター:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

セクション ID。

**戻り値:**  
java.util.UUID

### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

セクションの最初のスライドを返します。

**戻り値:**  
[ISlide](../../com.aspose.slides/islide)

### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

セクション内のスライドのリストを返します。

**戻り値:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - スライドのリスト。