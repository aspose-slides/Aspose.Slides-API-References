---
title: Control
type: docs
weight: 0
url: /php-java/control/
---

# Control class

 Represents an ActiveX control.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getActiveXControlBinary](/slides/php-java/control/getactivexcontrolbinary/)() | byte | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
| [getClassId](/slides/php-java/control/getclassid/)() | UUID | Gets class id of this control. Read-only java.util.UUID. |
| [getFrame](/slides/php-java/control/getframe/)() | IShapeFrame | Returns or sets control's frame. Read/write IShapeFrame. |
| [getName](/slides/php-java/control/getname/)() | String | Gets or sets the name of this control. Read/write String. |
| [getPersistence](/slides/php-java/control/getpersistence/)() | int | Gets the method used to store properties of the ActiveX control. Read only PersistenceType. |
| [getPresentation](/slides/php-java/control/getpresentation/)() | IPresentation |  |
| [getProperties](/slides/php-java/control/getproperties/)() | IControlPropertiesCollection | Returns a collection of ActiveX properties. Read-only IControlPropertiesCollection. Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null. |
| [getSlide](/slides/php-java/control/getslide/)() | IBaseSlide |  |
| [getSubstitutePictureFormat](/slides/php-java/control/getsubstitutepictureformat/)() | IPictureFillFormat | Returns Control image fill properties object. Read-only IPictureFillFormat. |
| [setClassId](/slides/php-java/control/setclassid/)(UUID) | void | Gets class id of this control. Read-only java.util.UUID. |
| [setFrame](/slides/php-java/control/setframe/)(IShapeFrame) | void | Returns or sets control's frame. Read/write IShapeFrame. |
| [setName](/slides/php-java/control/setname/)(String) | void | Gets or sets the name of this control. Read/write String. |
