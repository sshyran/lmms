INCLUDE(BuildPlugin)

BUILD_PLUGIN(dualfilter DualFilter.cpp DualFilterControls.cpp DualFilterControlDialog.cpp MOCFILES DualFilterControls.h DualFilterControlDialog.h EMBEDDED_RESOURCES artwork.png logo.png)
