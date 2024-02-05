---
title: LoadingStreamBehavior
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/loadingstreambehavior/
---

## LoadingStreamBehavior class

 The  java.io.InputStream passed to a method is considered as a Binary Large Object (BLOB) (see
  IBlobManagementOptions description). Values of this enumeration identify how 
 the  java.io.InputStream should be treated when it passed to the method. Depending on the
 requirements, different decisions could be made to provide the most efficient behavior. 
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[ReadStreamAndRelease](#ReadStreamAndRelease) | 0 | The stream will be read to the end and then released - i.e. it will be guaranteed that this stream will not be used by IPresentation instance in the future. It can be closed by the client code or used in any other way. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object. } finally { if (pres != null) pres.dispose(); } |
[KeepLocked](#KeepLocked) | 1 | The stream will be locked inside the IPresentation object, i.e. the ownership of the stream will be transferred. The IPresentation object will be responsible to correctly dispose the stream when this object will be disposed itself. This behavior is extremely useful when you need to serialize a large BLOB file (such as a large video or audio -see IBlobManagementOptions description) and want to prevent loading this file into memory or other performance issues. You may just open the java.io.FileInputStream for this file and pass to a method, choosing LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method. // The fileStream will be used for saving, what will prevent high memory consumption pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); } |


---


### ReadStreamAndRelease {#ReadStreamAndRelease}
The stream will be read to the end and then released - i.e. it will be guaranteed that this stream will not be used by IPresentation instance in the future. It can be closed by the client code or used in any other way. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object. } finally { if (pres != null) pres.dispose(); }

---

### KeepLocked {#KeepLocked}
The stream will be locked inside the IPresentation object, i.e. the ownership of the stream will be transferred. The IPresentation object will be responsible to correctly dispose the stream when this object will be disposed itself. This behavior is extremely useful when you need to serialize a large BLOB file (such as a large video or audio -see IBlobManagementOptions description) and want to prevent loading this file into memory or other performance issues. You may just open the java.io.FileInputStream for this file and pass to a method, choosing LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method. // The fileStream will be used for saving, what will prevent high memory consumption pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); }

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
List, ArrayList


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


