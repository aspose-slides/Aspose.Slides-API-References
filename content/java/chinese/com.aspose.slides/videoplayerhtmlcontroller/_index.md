---
title: VideoPlayerHtmlController
second_title: Aspose.Slides for Java API 参考
description: 此类允许将视频和音频文件导出为 HTML
type: docs
url: /zh/com.aspose.slides/videoplayerhtmlcontroller/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)  
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

此类允许将视频和音频文件导出为 HTML
## 构造函数

| 构造函数 | 说明 |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Creates a new instance of controller |
## 方法

| 方法 | 说明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


Creates a new instance of controller

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| path | java.lang.String | 生成视频和音频文件的路径 |
| fileName | java.lang.String | HTML 文件的名称 |
| baseUri | java.lang.String | 用于生成链接的基本 URI |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


用于写入 HTML 文档头部。每次演示文稿转换调用一次。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


用于写入 HTML 文档底部。每次演示文稿转换调用一次。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


用于写入 HTML 幻灯片头部。每个幻灯片调用一次。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


用于写入 HTML 幻灯片底部。每个幻灯片调用一次。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片图像生成将完成，插入添加的 HTML 片段并在之前的图像上方开始新的图像。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片图像生成将完成，插入添加的 HTML 片段并在之前的图像上方开始新的图像。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


此函数在将形状渲染为 SVG 之前调用，以允许用户控制生成的 SVG。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


确定对象应存储的位置。此方法对每个对象 id 调用一次。不能保证不会出现具有相同数据、semanticName 和 contentType 但 id 不同的两个对象。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**返回:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


返回指向外部对象的 URL。如果 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 返回 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link)，则始终调用此方法；如果返回 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 且无法嵌入，则可能调用此方法。对于同一对象 id 可以多次调用。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**返回:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


保存外部对象。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |