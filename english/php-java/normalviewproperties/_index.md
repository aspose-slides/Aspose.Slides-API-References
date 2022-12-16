---
title: NormalViewProperties
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/normalviewproperties/
---

## NormalViewProperties class

 Represents normal view properties. The normal view consists of
 three content regions: the slide itself, a side content region, and a bottom content region.
 

 The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
 
```php
  // Instantiate a presentation object that represents a presentation file
  $pres = new Presentation("demo.pptx");
  try {
    $pres->getViewProperties()->getNormalViewProperties()->setHorizontalBarState(SplitterBarStateType.Restored);
    $pres->getViewProperties()->getNormalViewProperties()->setVerticalBarState(SplitterBarStateType.Maximized);
    $pres->getViewProperties()->getNormalViewProperties()->getRestoredTop()->setAutoAdjust(true);
    $pres->getViewProperties()->getNormalViewProperties()->getRestoredTop()->setDimensionSize(80);
    $pres->getViewProperties()->getNormalViewProperties()->setShowOutlineIcons(true);
    $pres->save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Methods

| Name | Description |
| --- | --- |
| [getHorizontalBarState](gethorizontalbarstate)() | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| [getPreferSingleView](getprefersingleview)() | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean. |
| [getRestoredLeft](getrestoredleft)() | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read opnly INormalViewRestoredProperties. |
| [getRestoredTop](getrestoredtop)() | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read only INormalViewRestoredProperties. |
| [getShowOutlineIcons](getshowoutlineicons)() | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean. |
| [getSnapVerticalSplitter](getsnapverticalsplitter)() | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean. |
| [getVerticalBarState](getverticalbarstate)() | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
| [setHorizontalBarState](sethorizontalbarstate)(int) | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| [setPreferSingleView](setprefersingleview)(boolean) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean. |
| [setShowOutlineIcons](setshowoutlineicons)(boolean) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean. |
| [setSnapVerticalSplitter](setsnapverticalsplitter)(boolean) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean. |
| [setVerticalBarState](setverticalbarstate)(int) | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
