---
title: IColorOperation
second_title: Aspose.Slides for Android via Java API Reference
description: 색상 변환에 사용되는 다양한 색상 작업을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icoloroperation/
---```
public interface IColorOperation
```

색상 변환에 사용되는 다양한 색상 작업을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOperationType()](#getOperationType--) | 작업의 유형을 반환하거나 설정합니다. |
| [getParameter()](#getParameter--) | 작업의 매개변수를 반환합니다. |
### getOperationType() {#getOperationType--}
```
public abstract int getOperationType()
```


작업의 유형을 반환하거나 설정합니다. 읽기 전용 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**반환:**
int
### getParameter() {#getParameter--}
```
public abstract float getParameter()
```


작업의 매개변수를 반환합니다. 읽기 전용 float.

**반환:**
float