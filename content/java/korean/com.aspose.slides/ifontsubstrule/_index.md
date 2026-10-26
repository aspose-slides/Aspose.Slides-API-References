---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Reference
description: Represents font subtituition information
type: docs
url: /ko/com.aspose.slides/ifontsubstrule/
---
```
public interface IFontSubstRule
```

글꼴 대체 정보를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 대체할 폰트 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | 대체에 사용할 폰트 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 대체에 적용할 규칙 읽기 전용 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

대체할 폰트 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

대체에 사용할 폰트 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

대체에 적용할 규칙 읽기 전용 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**반환:**
int