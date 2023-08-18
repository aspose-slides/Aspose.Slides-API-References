---
title: addFromHtml
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/addfromhtml/
---

## addFromHtml(String htmlText, [ExternalResourceResolver](../../externalresourceresolver) resolver, String uri)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide](../../slide)


---


## addFromHtml(String htmlText, [HtmlExternalResolver](../../htmlexternalresolver) resolver, String uri)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide](../../slide)


---


## addFromHtml(String htmlText)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |

### Result
[Slide](../../slide)


---


## addFromHtmlFromStream (SlideCollection slidecollection, ReadStream htmlStream, [ExternalResourceResolver](../../externalresourceresolver) resolver, String uri, Function callback)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


## addFromHtmlFromStream (SlideCollection slidecollection, ReadStream htmlStream, [HtmlExternalResolver](../../htmlexternalresolver) resolver, String uri, Function callback)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


## addFromHtmlFromStream (SlideCollection slidecollection, ReadStream htmlStream, Function callback)  function

 Creates slides from HTML text and adds them to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide](../../slide)


---


