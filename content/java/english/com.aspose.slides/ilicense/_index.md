---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /com.aspose.slides/ilicense/
---```
public interface ILicense
```

Provides methods to license the component.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [resetLicense()](#resetLicense--) | Reset the license |
| [isLicensed()](#isLicensed--) | Check if licence is applied to component |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Licenses the component.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode.

--------------------

Tries to find the license in the following locations:

1. Explicit path.

2. The folder of the component assembly.

3. The folder of the client's calling assembly.

4. The folder of the entry assembly.

5. An embedded resource in the client's calling assembly. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Licenses the component.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream that contains the license.

--------------------

Use this method to load a license from a stream. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Reset the license

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Use this method to reset license in component

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Check if licence is applied to component

**Returns:**
boolean - true if component is licensed, otherwise false
