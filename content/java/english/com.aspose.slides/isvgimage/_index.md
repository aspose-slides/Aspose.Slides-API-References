---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
weight: 1052
url: /com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Represents an SVG image.
## Methods

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during SVG documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified SVG. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Returns SVG content. Read-only String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Returns SVG data. Read-only byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Return callback interface used to resolve external resources during SVG documents import. Read-only [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Returns base URI of the specified SVG. Used to resolve relative links. Read-only String.

**Returns:**
java.lang.String
