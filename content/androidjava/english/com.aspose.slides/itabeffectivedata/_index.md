---
title: ITabEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective texts tabulation stop properties.
type: docs
weight: 1060
url: /com.aspose.slides/itabeffectivedata/
---
**All Implemented Interfaces:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Immutable object which contains effective text's tabulation stop properties.

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Returns position of a tab. |
| [getAlignment()](#getAlignment--) | Returns align style of a tab. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Returns position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read-only double.

**Returns:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returns align style of a tab. Read-only [TabAlignment](../../com.aspose.slides/tabalignment).

**Returns:**
int
