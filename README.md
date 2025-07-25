# owl-carousel-item-same-height

```CSS
.safeguard_in .owl-stage {
  display: flex !important;
  align-items: stretch !important;
  margin: 10px 0;
}

.safeguard_in .owl-item {
  display: flex !important;
  align-items: stretch !important;
}

.safeguard_item
{
  height: 100%;
  border-radius: 10px;
  overflow: hidden;
  background-color: white;
}
```
# Arrow Icon Change

``` Javascript
<script>
      $(".owl-carousel").owlCarousel({
        loop: true,
        margin: 30,
        nav: true,
        dots: false,
        navText: [
          '<i class="ri-arrow-left-line"></i>',
          '<i class="ri-arrow-right-line"></i>',
        ],
        responsive: {
          0: {
            items: 1,
          },
          600: {
            items: 2,
          },
          1000: {
            items: 3,
          },
        },
      });
    </script>
```
