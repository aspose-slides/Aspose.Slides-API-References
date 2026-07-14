---
title: ITextSearchOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 프레젠테이션 슬라이드 또는 텍스트 프레임에서 텍스트를 검색하는 데 사용할 수 있는 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

프레젠테이션, 슬라이드 또는 텍스트 프레임에서 텍스트를 검색하는 데 사용할 수 있는 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | true를 설정하면 대소문자 구분 검색을 사용하고, false - 그렇지 않음. |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | true를 설정하면 대소문자 구분 검색을 사용하고, false - 그렇지 않음. |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | true를 설정하면 전체 단어만 매치하고, false - 그렇지 않음. |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | true를 설정하면 전체 단어만 매치하고, false - 그렇지 않음. |
| [getIncludeNotes()](#getIncludeNotes--) | 텍스트 검색, 교체 또는 강조 표시 작업을 수행할 때 슬라이드 노트에 포함된 텍스트를 포함하도록 true를 설정합니다. |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | 텍스트 검색, 교체 또는 강조 표시 작업을 수행할 때 슬라이드 노트에 포함된 텍스트를 포함하도록 true를 설정합니다. |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```


true를 설정하면 대소문자 구분 검색을 사용하고, false - 그렇지 않음. 읽기/쓰기 boolean.

**반환:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


true를 설정하면 대소문자 구분 검색을 사용하고, false - 그렇지 않음. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


true를 설정하면 전체 단어만 매치하고, false - 그렇지 않음. 읽기/쓰기 boolean.

**반환:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


true를 설정하면 전체 단어만 매치하고, false - 그렇지 않음. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


텍스트 검색, 교체 또는 강조 표시 작업을 수행할 때 슬라이드 노트에 포함된 텍스트를 포함하도록 true를 설정합니다. 기본값은 false입니다.

**반환:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


텍스트 검색, 교체 또는 강조 표시 작업을 수행할 때 슬라이드 노트에 포함된 텍스트를 포함하도록 true를 설정합니다. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |