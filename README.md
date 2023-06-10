# bcm5974 Input Area Limit Patch

## Description

This patch for the `bcm5974` driver aims to enhance user experience by preventing accidental mouse movements or clicks when typing. It does this by disabling the touchpad functionality near the left and right edges of the touchpad.

The touchpad area limits are defined as follows:

- Left edge: x < -6000
- Right edge: x > 6500
