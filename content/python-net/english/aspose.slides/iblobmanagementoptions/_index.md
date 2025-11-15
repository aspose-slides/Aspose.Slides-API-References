---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iblobmanagementoptions/
---


## IBlobManagementOptions class

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an 
            audio, video or presentation itself. A number of techniques are used to optimize memory consumption 
            while working with BLOBs - which was already stored in the presentation or be added later programmatically. 
            Using [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions) you can change a different behavior aspects regarding BLOBs 
            handling for the [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance lifetime.

The IBlobManagementOptions type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | This property defines if an instance of the Presentation class can be an owner of the source - file <br/>            or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps <br/>            to improve memory consumption and performance while working with BLOBs, but the source (stream or file) <br/>            can't be changed during Presentation's instance lifetime. This is an example: |
| [`is_temporary_files_allowed`](/slides/python-net/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | This property defines if temporary files can be created while working with BLOBs, what greatly <br/>            decreases  the memory consumption but requires permissions to create files.<br/>            All files will be deleted after work with the presentation will be finished. |
| [`temp_files_root_path`](/slides/python-net/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | The root path where temporary files will be created. System temorary directory will be used by default. <br/>            Hosting process should have permissions to <br/>            create files and folders there. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs<br/>            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary<br/>            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use<br/>            this property to tailor behavior to your environment or requirements. |


### See Also
* class [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

