---
title: IBehaviorProperty
second_title: Aspose.Sildes for Java API Reference
description: p
 Represent property types for animation behavior.
type: docs
weight: 662
url: /java/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Represent property types for animation behavior. Follows the list of properties from https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx and https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Value of the property |
| [isCustom()](#isCustom--) | Shows if this property does not belong to the predefined properties list in the specification: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Value of the property

**Returns:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Shows if this property does not belong to the predefined properties list in the specification: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Returns:**
boolean
