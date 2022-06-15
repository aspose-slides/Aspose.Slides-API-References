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
| [getActiveXControlBinary](/php-java/control/getactivexcontrolbinary/)() | byte | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
| [getClassId](/php-java/control/getclassid/)() | UUID | Gets class id of this control. Read-only java.util.UUID. |
| [getFrame](/php-java/control/getframe/)() | IShapeFrame | Returns or sets control's frame. Read/write IShapeFrame. |
| [getName](/php-java/control/getname/)() | String | Gets or sets the name of this control. Read/write String. |
| [getPersistence](/php-java/control/getpersistence/)() | int | Gets the method used to store properties of the ActiveX control. Read only PersistenceType. |
| [getPresentation](/php-java/control/getpresentation/)() | IPresentation |  |
| [getProperties](/php-java/control/getproperties/)() | IControlPropertiesCollection | Returns a collection of ActiveX properties. Read-only IControlPropertiesCollection. Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null. |
| [getSlide](/php-java/control/getslide/)() | IBaseSlide |  |
| [getSubstitutePictureFormat](/php-java/control/getsubstitutepictureformat/)() | IPictureFillFormat | Returns Control image fill properties object. Read-only IPictureFillFormat. |
| [setClassId](/php-java/control/setclassid/)(UUID) | void | Gets class id of this control. Read-only java.util.UUID. |
| [setFrame](/php-java/control/setframe/)(IShapeFrame) | void | Returns or sets control's frame. Read/write IShapeFrame. |
| [setName](/php-java/control/setname/)(String) | void | Gets or sets the name of this control. Read/write String. |
