---
title: ISlideText
second_title: Aspose.Slides for Java API 참조
description: 슬라이드에서 추출된 텍스트를 나타냅니다
type: docs
url: /ko/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

슬라이드에서 추출된 텍스트를 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) | 슬라이드 도형의 텍스트 |
| [getMasterText()](#getMasterText--) | 이 슬라이드의 마스터 페이지 도형 텍스트 |
| [getLayoutText()](#getLayoutText--) | 이 슬라이드의 레이아웃 페이지 도형 텍스트 |
| [getNotesText()](#getNotesText--) | 이 슬라이드의 노트 페이지 도형 텍스트 |
| [getCommentsText()](#getCommentsText--) | 슬라이드 코멘트 텍스트 |
### getText() {#getText--}
```
public abstract String getText()
```


슬라이드 도형의 텍스트

**반환:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


이 슬라이드의 마스터 페이지 도형 텍스트

**반환:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


이 슬라이드의 레이아웃 페이지 도형 텍스트

**반환:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


이 슬라이드의 노트 페이지 도형 텍스트

**반환:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


슬라이드 코멘트 텍스트

--------------------

텍스트가 Arranged 모드로 추출될 때 이 필드는 비어 있습니다.

**반환:**
java.lang.String