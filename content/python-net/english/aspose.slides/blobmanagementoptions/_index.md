---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/blobmanagementoptions/
---


## BlobManagementOptions class

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

The BlobManagementOptions type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides/blobmanagementoptions/__init__/#) | Creates new default blob management options. |

## Properties

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | This property defines if an instance of the Presentation class can be an owner of the source - file <br/>            or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps <br/>            to improve memory consumption and performance while working with BLOBs, but the source (stream or file) <br/>            can't be changed during Presentation's instance lifetime. |
| [`is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | This property defines if temporary files can be created while working with BLOBs, what greatly <br/>            decreases  the memory consumption but requires permissions to create files.<br/>            All files will be deleted after work with the presentation will be finished. |
| [`temp_files_root_path`](/slides/python-net/aspose.slides/blobmanagementoptions/temp_files_root_path/) | The root path where temporary files will be created. System temorary directory will be used by default. <br/>            Hosting process should have permissions to <br/>            create files and folders there. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs <br/>            loading into memory as default behavior and only when it reaches the limit defined by this property, <br/>            other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient <br/>            way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what <br/>            may be undesirable. Using this property, you may set the optimal behavior for your environment or <br/>            other requirements.<br/>            <br/>            This property will be ignored if [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions#is_temporary_files_allowed) is<br/>            set to false. It makes no sense to limit the maximum BLOBs in memory, because if <br/>            [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions#is_temporary_files_allowed) is set to false, the memory is the only place <br/>            where BLOBs can be stored.<br/>            Default value is 629,145,600 bytes (600Mb). |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

