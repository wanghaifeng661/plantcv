## Create a rectangular Region of Interest (ROI)

**plantcv.roi.rectangle**(*x, y, h, w, img*)

**returns** roi_contour, roi_hierarchy

- **Parameters:**
    - x - The x-coordinate of the upper left corner of the rectangle.
    - y - The y-coordinate of the upper left corner of the rectangle.
    - h - The height of the rectangle.
    - w - The width of the rectangle.
    - img - An RGB or grayscale image to plot the ROI on in debug mode.
- **Context:**
    - Used to define a region of interest in the image.

**Reference Image**

![Screenshot](img/documentation_images/rectangle/original_image.jpg)

```python
import plantcv.roi

roi_contour, roi_hierarchy = plantcv.roi.rectangle(x=100, y=100, h=200, w=200, img=rgb_img)
```

![Screenshot](img/documentation_images/rectangle/image_with_roi.jpg)
