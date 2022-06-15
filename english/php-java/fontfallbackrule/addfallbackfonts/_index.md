---
title: addFallBackFonts
type: docs
weight: 30
url: /php-java/fontfallbackrule/addfallbackfonts/
---

# addFallBackFonts(java.lang.String) method

 Adds a new font(s) to the list of FallBack fonts.
 

 
```php
  // Create new instance of FontFallBackRule
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho");
  // Add a second font to the rule
  $newRule->addFallBackFonts("MS Gothic");
  // Add a third and fourth fonts to the rule
  $newRule->addFallBackFonts("Tahoma, Times New Roman");
```

##  Parameters

| name | description |
| --- | --- |
| fontName | Font's name or names (delimited by comma) for FallBack |


# addFallBackFonts(java.lang.String[]) method

 Adds a new fonts to the list of FallBack fonts.
 

 
```php
  // Create new instance of FontFallBackRule
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho");
  // Add of another three fonts to the rule
  $newRule->addFallBackFonts(new String[]{ "MS Gothic", "Tahoma, Times New Roman" });
```

##  Parameters

| name | description |
| --- | --- |
| fontNames | Font's name or names (delimited by comma) for FallBack |


