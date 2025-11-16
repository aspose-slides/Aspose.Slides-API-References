---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/fontsmanager/get_substitutions/
weight: 60
---


## get_substitutions {#}
Gets the information about fonts that will be replaced on the presentation's rendering.

### Returns

Collection of all fonts substitution [`FontSubstitutionInfo`](/slides/python-net/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions {#listint}
Gets the information about fonts that will be replaced during rendering of the specified slides.

### Returns

A collection of all font substitutions ([`FontSubstitutionInfo`](/slides/python-net/aspose.slides/fontsubstitutioninfo)) for the specified slides.



```python
def get_substitutions(self, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slides | **List[int]** | An array of slide indexes for which to retrieve font substitution information, starting from 1. |



### See Also
* class [`FontsManager`](/slides/python-net/aspose.slides/fontsmanager)
* class [`FontSubstitutionInfo`](/slides/python-net/aspose.slides/fontsubstitutioninfo)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

