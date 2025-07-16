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
| [`is_temporary_files_allowed`](/slides/python-net/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | This property defines if temporary files can be created while working with BLOBs, what greatly <br/>            decreases  the memory consumption but requires permissions to create files.<br/>All files will be deleted after work with the presentation will be finished. |
| [`temp_files_root_path`](/slides/python-net/aspose.slides/blobmanagementoptions/temp_files_root_path/) | The root path where temporary files will be created. System temorary directory will be used by default. <br/>            Hosting process should have permissions to <br/>            create files and folders there. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs<br/>            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary<br/>            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use<br/>            this property to tailor behavior to your environment or requirements. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

