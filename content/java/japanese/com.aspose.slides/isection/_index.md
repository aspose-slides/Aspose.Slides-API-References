---
title: ISection
second_title: Aspose.Slides for Java API リファレンス
description: スライドのセクションを表します。
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
| [getSlidesListOfSection()](#getSlidesListOfSection--) | セクション内のスライドのリストを返します。 |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
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

セクション内のスライドのリストを返します。

**戻り値:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - スライドのリスト [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)