---
title: OleObjectFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/oleobjectframe/
---

## OleObjectFrame class

 Represents an OLE object on a slide.
 

## Functions

| Name | Description |
| --- | --- |
| [getEmbeddedData](getembeddeddata)() | Gets or sets information about OLE embedded data. Read/write IOleEmbeddedDataInfo. |
| [getEmbeddedFileLabel](getembeddedfilelabel)() | Returns the file name of embedded OLE object |
| [getEmbeddedFileName](getembeddedfilename)() | Returns the path of embedded OLE object |
| [getLinkFileName](getlinkfilename)() | Returns the full path to a linked file. Short file name will be used. Read-only String. |
| [getLinkPathLong](getlinkpathlong)() | Returns the full path to a linked file. Long file name will be used. Read/write String. |
| [getLinkPathRelative](getlinkpathrelative)() | Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly String. In the Ppt presentations, some Ole object links may have a relative representation. |
| [getObjectName](getobjectname)() | Returns or sets the name of an object. Read/write String. |
| [getObjectProgId](getobjectprogid)() | Returns the ProgID of an object. Read only String. |
| [getSubstitutePictureFormat](getsubstitutepictureformat)() | Returns OleObject image fill properties object. Read-only IPictureFillFormat. |
| [getSubstitutePictureTitle](getsubstitutepicturetitle)() | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |
| [getUpdateAutomatic](getupdateautomatic)() | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |
| [isObjectIcon](isobjecticon)() | Determines whether an object is visible as icon. Read/write boolean. |
| [isObjectLink](isobjectlink)() | Determines whether an object is linked to external file. Read-only boolean. |
| [setEmbeddedData](setembeddeddata)([OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Sets information about OLE embedded data. |
| [setLinkPathLong](setlinkpathlong)(String) | Returns the full path to a linked file. Long file name will be used. Read/write String. |
| [setObjectIcon](setobjecticon)(boolean) | Determines whether an object is visible as icon. Read/write boolean. |
| [setObjectName](setobjectname)(String) | Returns or sets the name of an object. Read/write String. |
| [setObjectProgId](setobjectprogid)(String) | Returns the ProgID of an object. Read only String. |
| [setSubstitutePictureTitle](setsubstitutepicturetitle)(String) | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |
| [setUpdateAutomatic](setupdateautomatic)(boolean) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |
