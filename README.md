# React Compiler Not Working

## Description

When modifying the content in `.module.scss`, the tsx file that imports it will be recompiled, but the hash in `className` has not changed, resulting in the new style not taking effect and the old style being lost.

Adding .css or .scss to the includes option of the plugin can solve this problem, but this will cause the react compiler to fail.

## Note

When not using the react compiler, the above problem will not occur even if .css or .scss is not included in the includedes option of the plugin
