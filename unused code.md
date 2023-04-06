``` html
    <!-- TEMPLATE -->
    <div class="template-mobile">
      <img src="design/mobile-design.jpg" alt="" />
    </div>
    <div class="template-desktop">
      <img src="design/desktop-design.jpg" alt="" />
    </div>
    <!-- END TEMPLATE -->
```






``` css

/* ================ */
/* Design Templates
Used to refine designs 
live in browser */
/* ================ */

.template-mobile {
  width: 375px; /* Adjust to image dimensions */
  height: 667px; /* Adjust to image dimensions */
  position: absolute;
  opacity: 0.4;
  z-index: 1;
  /* top: 10px; */
  display: none;
}

.template-desktop {
  width: 1440px; /* Adjust to image dimensions */
  height: 720px; /* Adjust to image dimensions */
  position: absolute;
  opacity: .5;
  z-index: 99;
  /* top: 10px; */
  display: none;
}

```