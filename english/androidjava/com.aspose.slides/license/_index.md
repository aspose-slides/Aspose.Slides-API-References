---
title: License
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
type: docs
weight: 275
url: /androidjava/com.aspose.slides/license/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Provides methods to license the component.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [getVersion()](#getVersion--) | Returns version of Aspose.Slides for Java. |
| [resetLicense()](#resetLicense--) | Reset the license Use this method to reset license in component |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenses the component.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream that contains the license. Use null to switch to evaluation mode. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licenses the component.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namePath | java.lang.String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Returns version of Aspose.Slides for Java.

**Returns:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Reset the license Use this method to reset license in component

```
License license = new License();
 license.resetLicense();
```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Check if licence is applied to component

**Returns:**
boolean
