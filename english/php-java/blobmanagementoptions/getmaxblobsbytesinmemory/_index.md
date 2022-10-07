---
title: getMaxBlobsBytesInMemory
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/blobmanagementoptions/getmaxblobsbytesinmemory/
---

## getMaxBlobsBytesInMemory()  method

 Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs 
 loading into memory as default behavior and only when it reaches the limit defined by this property, 
 other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient 
 way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what 
 may be undesirable. Using this property, you may set the optimal behavior for your environment or 
 other requirements.
 
 This property will be ignored if  IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is
 set to false. It makes no sense to limit the maximum BLOBs in memory, because if 
  IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is set to false, the memory is the only place 
 where BLOBs can be stored.
 Default value is 629,145,600 bytes (600Mb).

### Returns
long


---


