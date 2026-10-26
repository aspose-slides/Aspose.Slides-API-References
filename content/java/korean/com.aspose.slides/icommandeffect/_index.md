---
title: ICommandEffect
second_title: Aspose.Slides Java API 레퍼런스
description: 애니메이션 동작에 대한 명령 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icommandeffect/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

애니메이션 동작에 대한 명령 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 명령 효과 유형을 정의합니다. |
| [setType(byte value)](#setType-byte-) | 명령 효과 유형을 정의합니다. |
| [getCommandString()](#getCommandString--) | 명령 문자열을 정의합니다. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | 명령 문자열을 정의합니다. |
| [getShapeTarget()](#getShapeTarget--) | 명령 효과의 모양 대상을 정의합니다. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | 명령 효과의 모양 대상을 정의합니다. |
### getType() {#getType--}
```
public abstract byte getType()
```

명령 효과 유형을 정의합니다. 읽기/쓰기 [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**반환값:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

명령 효과 유형을 정의합니다. 읽기/쓰기 [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

명령 문자열을 정의합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

명령 문자열을 정의합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

명령 효과의 모양 대상을 정의합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환값:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

명령 효과의 모양 대상을 정의합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |