---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /ja/com.aspose.slides/isection/
---```
public interface ISection
```

スライドのセクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | セクションの名前。 |
| [setName(String value)](#setName-java.lang.String-) | セクションの名前。 |
| [getSectionId()](#getSectionId--) | セクション ID。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | セクションの最初のスライドを返します。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | セクション内のスライドの一覧を返します。 |
### getName() {#getName--}
```
public abstract String getName()
```

セクションの名前。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

セクションの名前。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

セクション ID。

**戻り値:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

セクションの最初のスライドを返します。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

セクション内のスライドの一覧を返します。

**戻り値:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - スライドのリスト [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)