---
title: updateDocumentProperties
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/presentationinfo/updatedocumentproperties/
---

## updateDocumentProperties(DocumentProperties documentProperties)  method

 Updates properties of binded presentation.
 

 This sample shows how to call the  #updateDocumentProperties(IDocumentProperties) method to
 update the document properties returned by call of the  #readDocumentProperties method.
 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo("pres.pptx");
  $props = $info->readDocumentProperties();
  $props->setSubject("New subject");
  $props->setLastSavedTime(Calendar->getInstance()->getTime());
  $info->updateDocumentProperties($props);
  $info->writeBindedPresentation("new_pres.pptx");
```

### Returns
#readDocumentProperties


---


