---
title: DigitalSignatureCollection
type: docs
weight: 0
url: /php-java/digitalsignaturecollection/
---

# DigitalSignatureCollection class

 Represents a collection of digital signatures attached to a document.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/slides/php-java/digitalsignaturecollection/add/)(IDigitalSignature) | void | Adds the signature at the end of collection. |
| [clear](/slides/php-java/digitalsignaturecollection/clear/)() | void | Removes all signatures from collection. |
| [getSyncRoot](/slides/php-java/digitalsignaturecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/digitalsignaturecollection/get_item/)(int) | IDigitalSignature | Returns the signature by index. |
| [isSynchronized](/slides/php-java/digitalsignaturecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/digitalsignaturecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/digitalsignaturecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [removeAt](/slides/php-java/digitalsignaturecollection/removeat/)(int) | void | Removes the signature at the specified index. |
| [size](/slides/php-java/digitalsignaturecollection/size/)() | int | Returns the number of elements in the collection. Read-only int. |
