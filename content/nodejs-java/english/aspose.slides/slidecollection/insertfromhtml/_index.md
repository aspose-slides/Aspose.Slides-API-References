---
title: insertFromHtml
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/insertfromhtml/
---

## insertFromHtml(int index, String htmlText, [ExternalResourceResolver](../../externalresourceresolver) resolver, String uri)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide](../../slide)


---


## insertFromHtml(int index, String htmlText, [HtmlExternalResolver](../../htmlexternalresolver) resolver, String uri)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide](../../slide)


---


## insertFromHtml(int index, String htmlText)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |

### Result
[Slide](../../slide)


---


## insertFromHtmlFromStream (SlideCollection slidecollection, int index, ReadStream htmlStream, [ExternalResourceResolver](../../externalresourceresolver) resolver, String uri, Function callback)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


## insertFromHtmlFromStream (SlideCollection slidecollection, int index, ReadStream htmlStream, [HtmlExternalResolver](../../htmlexternalresolver) resolver, String uri, Function callback)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


## insertFromHtmlFromStream (SlideCollection slidecollection, int index, ReadStream htmlStream, Function callback)  function

 Creates slides from HTML text and inserts them to the collection at the specified position.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


