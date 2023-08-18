---
title: checkWriteProtection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationinfo/checkwriteprotection/
---

## checkWriteProtection(String password)  function

 Checks whether a password to modify is correct for a write protected presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password to check. 1. You should check the ( #isWriteProtected) property before calling this function. 2. When password is null or empty, this function returns false. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | If a presentation is protected by a password to open or format does not support write protection |


---


