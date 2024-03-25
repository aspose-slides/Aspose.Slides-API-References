---
title: PresentationLockingBehavior
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationlockingbehavior/
---

## PresentationLockingBehavior class

 Represents the behavior regarding treating the  IPresentation source (file or 
  java.io.InputStream) while loading and working with an instance of  IPresentation.
 The source is the parameter passed to the  IPresentation constructor. In the 
 example below, the source is the "pres.pptx" file:
 For this example, the source ("pres.pptx" file) will be locked for a  IPresentation 
 instance lifetime, i.e. can't be changed or deleted by the other process.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[LoadAndRelease](#LoadAndRelease) | 0 | The source will be locked only for a time of IPresentation constructor execution. If ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) is set to false, all BLOBs will be loaded into memory. Otherwise, other means such a temporary files might be used.This behavior is slower than PresentationLockingBehavior#KeepLocked, and if it is possible to pass the ownership of the source to IPresentation, it is recommended to use PresentationLockingBehavior#KeepLocked. |
[KeepLocked](#KeepLocked) | 1 | The source will be locked for a whole lifetime of IPresentation instance, until it will be disposed. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) is must be set to true for using this behavior, otherwise exception will be thrown.This behavior is recommended, it is faster and consumes less memory than PresentationLockingBehavior#LoadAndRelease. |


---


### LoadAndRelease {#LoadAndRelease}
The source will be locked only for a time of IPresentation constructor execution. If ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) is set to false, all BLOBs will be loaded into memory. Otherwise, other means such a temporary files might be used.This behavior is slower than PresentationLockingBehavior#KeepLocked, and if it is possible to pass the ownership of the source to IPresentation, it is recommended to use PresentationLockingBehavior#KeepLocked.

---

### KeepLocked {#KeepLocked}
The source will be locked for a whole lifetime of IPresentation instance, until it will be disposed. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) is must be set to true for using this behavior, otherwise exception will be thrown.This behavior is recommended, it is faster and consumes less memory than PresentationLockingBehavior#LoadAndRelease.

---


### Clone {#Clone}

| Name | Description |
| --- | --- |
| Clone() |  |

 **Result:**
T


---


### CloneTo {#CloneTo}

| Name | Description |
| --- | --- |
| CloneTo(T) |  |


---


### format {#format}

| Name | Description |
| --- | --- |
| format(java.lang.Class<?>, long, String) |  |

 **Result:**
String


---


### format {#format}

| Name | Description |
| --- | --- |
| format(Type, Object, String) |  |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName(java.lang.Class<?>, long) |  |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName(Type, Object) |  |

 **Result:**
String


---


### getNames {#getNames}

| Name | Description |
| --- | --- |
| getNames(java.lang.Class<?>) |  |

 **Result:**
ArrayList, List


---


### getNames {#getNames}

| Name | Description |
| --- | --- |
| getNames(Type) |  |

 **Result:**
String


---


### getUnderlyingType {#getUnderlyingType}

| Name | Description |
| --- | --- |
| getUnderlyingType(java.lang.Class<?>) |  |

 **Result:**
Class


---


### getUnderlyingType {#getUnderlyingType}

| Name | Description |
| --- | --- |
| getUnderlyingType(Type) |  |

 **Result:**
Type


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue(java.lang.Class<?>, String) |  |

 **Result:**
long


---


### getValues {#getValues}

| Name | Description |
| --- | --- |
| getValues(Type) |  |

 **Result:**
Array


---


### get_Caption {#get_Caption}

| Name | Description |
| --- | --- |
| get_Caption() |  |

 **Result:**
String


---


### get_Value {#get_Value}

| Name | Description |
| --- | --- |
| get_Value() |  |

 **Result:**
long


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined(java.lang.Class<?>, long) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined(Type, long) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined(Type, String) |  |

 **Result:**
boolean


---


### isDefined {#isDefined}

| Name | Description |
| --- | --- |
| isDefined(Type, Object) |  |

 **Result:**
boolean


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse(java.lang.Class<?>, String) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse(java.lang.Class<?>, String, Boolean) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse(Type, String) |  |

 **Result:**
long


---


### parse {#parse}

| Name | Description |
| --- | --- |
| parse(Type, String, Boolean) |  |

 **Result:**
long


---


### register {#register}

| Name | Description |
| --- | --- |
| register(Enum.AbstractEnum) |  |


---


### toObject {#toObject}

| Name | Description |
| --- | --- |
| toObject(Type, Object) |  |

 **Result:**
Object


---


### toString {#toString}

| Name | Description |
| --- | --- |
| toString(java.lang.Class<?>, long) |  |

 **Result:**
String


---


