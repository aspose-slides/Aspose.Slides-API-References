---
title: OleObjectFrame
type: docs
weight: 0
url: /php-java/oleobjectframe/
---

# OleObjectFrame class

 Represents an OLE object on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getEmbeddedData](/php-java/oleobjectframe/getembeddeddata/)() | IOleEmbeddedDataInfo | Gets or sets information about OLE embedded data. Read/write IOleEmbeddedDataInfo. |
| [getEmbeddedFileLabel](/php-java/oleobjectframe/getembeddedfilelabel/)() | String | Returns the file name of embedded OLE object |
| [getEmbeddedFileName](/php-java/oleobjectframe/getembeddedfilename/)() | String | Returns the path of embedded OLE object |
| [getLinkFileName](/php-java/oleobjectframe/getlinkfilename/)() | String | Returns the full path to a linked file. Short file name will be used. Read-only String. |
| [getLinkPathLong](/php-java/oleobjectframe/getlinkpathlong/)() | String | Returns the full path to a linked file. Long file name will be used. Read/write String. |
| [getObjectName](/php-java/oleobjectframe/getobjectname/)() | String | Returns or sets the name of an object. Read/write String. |
| [getObjectProgId](/php-java/oleobjectframe/getobjectprogid/)() | String | Returns the ProgID of an object. Read only String. |
| [getSubstitutePictureFormat](/php-java/oleobjectframe/getsubstitutepictureformat/)() | IPictureFillFormat | Returns OleObject image fill properties object. Read-only IPictureFillFormat. |
| [getSubstitutePictureTitle](/php-java/oleobjectframe/getsubstitutepicturetitle/)() | String | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |
| [getUpdateAutomatic](/php-java/oleobjectframe/getupdateautomatic/)() | boolean | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |
| [isObjectIcon](/php-java/oleobjectframe/isobjecticon/)() | boolean | Determines whether an object is visible as icon. Read/write boolean. |
| [isObjectLink](/php-java/oleobjectframe/isobjectlink/)() | boolean | Determines whether an object is linked to external file. Read-only boolean. |
| [setEmbeddedData](/php-java/oleobjectframe/setembeddeddata/)(IOleEmbeddedDataInfo) | void | Sets information about OLE embedded data. |
| [setLinkPathLong](/php-java/oleobjectframe/setlinkpathlong/)(String) | void | Returns the full path to a linked file. Long file name will be used. Read/write String. |
| [setObjectIcon](/php-java/oleobjectframe/setobjecticon/)(boolean) | void | Determines whether an object is visible as icon. Read/write boolean. |
| [setObjectName](/php-java/oleobjectframe/setobjectname/)(String) | void | Returns or sets the name of an object. Read/write String. |
| [setObjectProgId](/php-java/oleobjectframe/setobjectprogid/)(String) | void | Returns the ProgID of an object. Read only String. |
| [setSubstitutePictureTitle](/php-java/oleobjectframe/setsubstitutepicturetitle/)(String) | void | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |
| [setUpdateAutomatic](/php-java/oleobjectframe/setupdateautomatic/)(boolean) | void | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |
