---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: 검색 텍스트 결과를 가져오기 위해 사용되는 콜백 인터페이스입니다.
type: docs
url: /ko/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

검색 텍스트 결과를 가져오기 위해 사용되는 콜백 인터페이스입니다.
## 메서드

| Method | Description |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Callback method that receives data about the found text. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

찾은 텍스트에 대한 데이터를 받는 콜백 메서드입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe)에서 텍스트가 발견된. |
| sourceText | java.lang.String | 텍스트가 발견된 원본 텍스트. |
| foundText | java.lang.String | 찾은 텍스트. |
| textPosition | int | 찾은 텍스트의 위치. |