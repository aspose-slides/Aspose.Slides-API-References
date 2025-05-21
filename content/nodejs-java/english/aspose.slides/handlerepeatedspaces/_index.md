---
title: HandleRepeatedSpaces
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/handlerepeatedspaces/
---

## HandleRepeatedSpaces class

 Specifies how repeated regular space characters should be handled
 during Markdown export.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[None](#None) | 0 | All spaces are preserved as regular space characters without any changes. No transformation is applied, and multiple consecutive spaces are exported as-is. |
[AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 1 | Converts sequences of two or more consecutive regular spaces by alternating between regular space characters and non-breaking space entities ({@code &nbsp;}). The first space is always preserved as a regular space. |
[MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 2 | Converts sequences of two or more consecutive regular spaces by preserving the first space as a regular space character and replacing all subsequent spaces with non-breaking space entities ({@code &nbsp;}). |


---


### None {#None}
All spaces are preserved as regular space characters without any changes. No transformation is applied, and multiple consecutive spaces are exported as-is.

---

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
Converts sequences of two or more consecutive regular spaces by alternating between regular space characters and non-breaking space entities ({@code &nbsp;}). The first space is always preserved as a regular space.

---

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
Converts sequences of two or more consecutive regular spaces by preserving the first space as a regular space character and replacing all subsequent spaces with non-breaking space entities ({@code &nbsp;}).

---


