---
title: ImageCollection
type: docs
weight: 0
url: /php-java/imagecollection/
---

# ImageCollection class

 Represents collection of PPImage.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addImage](/php-java/imagecollection/addimage/)(IPPImage) | IPPImage | Adds a copy of an image from an another presentation. |
| [addImage](/php-java/imagecollection/addimage/)(BufferedImage) | IPPImage | Add an image to a presentation. |
| [addImage](/php-java/imagecollection/addimage/)(InputStream) | IPPImage | Add an image to a presentation from stream. |
| [addImage](/php-java/imagecollection/addimage/)(InputStream, int) | IPPImage | Creates and adds an image to a presentation from stream. |
| [addImage](/php-java/imagecollection/addimage/)(byte[]) | IPPImage | Adds an image to a presentation from specified buffer. |
| [addImage](/php-java/imagecollection/addimage/)(ISvgImage) | IPPImage | Add an image to a presentation from Svg object. |
| [getSyncRoot](/php-java/imagecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/imagecollection/get_item/)(int) | IPPImage | Gets the element at the specified index. Read-only IPPImage. |
| [isSynchronized](/php-java/imagecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/imagecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/imagecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [size](/php-java/imagecollection/size/)() | int | Returns a number of images in the collection. Read-only int. |