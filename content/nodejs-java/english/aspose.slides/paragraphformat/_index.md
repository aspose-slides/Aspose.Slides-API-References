---
title: ParagraphFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphformat/
---

## ParagraphFormat class

 This class contains the paragraph formatting properties. Unlike  IParagraphFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  ParagraphFormat#getEffective method 
 which returns a  IParagraphFormatEffectiveData instance.
| [ParagraphFormat]() | Initializes a new instance of ParagraphFormat class. |

### Result
ParagraphFormat


---


| [getAlignment] () Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

### Result
int


---


| [getBullet] () Returns bullet format of the paragraph. Read-only IBulletFormat. |

### Result
[BulletFormat]


---


| [getDefaultPortionFormat] () Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |

### Result
[PortionFormat]


---


| [getDefaultTabSize] () Returns or sets default tabulation size with no inheritance. Read/write float. |

### Result
float


---


| [getDepth] () Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

### Result
short


---


| [getEastAsianLineBreak] () Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| [getEffective] () Gets effective paragraph formatting data with the inheritance applied. |

### Result
[ParagraphFormatEffectiveData]


---


| [getFontAlignment] () Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

### Result
int


---


| [getHangingPunctuation] () Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| [getIndent] () Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

### Result
float


---


| [getLatinLineBreak] () Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| [getMarginLeft] () Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

### Result
float


---


| [getMarginRight] () Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

### Result
float


---


| [getRightToLeft] () Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| [getSpaceAfter] () Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

### Result
float


---


| [getSpaceBefore] () Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

### Result
float


---


| [getSpaceWithin] () Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

### Result
float


---


| [getTabs] () Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |

### Result
[TabCollection]


---


| [getVersion] ()  |

### Result
long


---


| [setAlignment] ([int]) Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |


---


| [setDefaultTabSize] ([float]) Returns or sets default tabulation size with no inheritance. Read/write float. |


---


| [setDepth] ([short]) Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |


---


| [setEastAsianLineBreak] ([byte]) Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| [setFontAlignment] ([int]) Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |


---


| [setHangingPunctuation] ([byte]) Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| [setIndent] ([float]) Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |


---


| [setLatinLineBreak] ([byte]) Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| [setMarginLeft] ([float]) Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |


---


| [setMarginRight] ([float]) Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |


---


| [setRightToLeft] ([byte]) Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| [setSpaceAfter] ([float]) Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


| [setSpaceBefore] ([float]) Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


| [setSpaceWithin] ([float]) Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |


---


