# Drawer Style Bootstrap 5 Modal
Drawer Style Bootstrap 5 Modal, simple and lightweight bootstrap 5 modal box.

View: [Demo](https://phyozawtun.github.io/Drawer-Style-Bootstrap-5-Modal/)

## Installation

CSS Style

```css
/* Modal Box */
.right .modal-dialog,
.left .modal-dialog {
    transition: transform .25s ease-out;
    position: fixed;
    margin: auto;
    height: 100%;
}
.modal.right .modal-content,
.modal.left .modal-content {
    overflow-y: auto;
  	border-radius: 0;
  	border: none;
    height: 100%;
}
.right .modal-dialog {
    transform: translateX(50px);
    right: 0;
}
.left .modal-dialog {
    transform: translateX(-50px);
    left: 0;
}
```



Right drawer example

```html
<div class="modal right">
  <div class="modal-dialog modal-sm w-100">
    <div class="modal-content">
	    ...
    </div>
  </div>
</div>
```



Left drawer example

```html
<div class="modal left">
  <div class="modal-dialog modal-sm w-100">
    <div class="modal-content">
	    ...
    </div>
  </div>
</div>
```





Drawer size examples

```html
<div class="modal left">
  <div class="modal-dialog modal-sm w-100">
    <div class="modal-content">
	    ...
    </div>
  </div>
</div>
```

```html
<div class="modal left">
  <div class="modal-dialog modal-md w-100">
    <div class="modal-content">
	    ...
    </div>
  </div>
</div>
```

```html
<div class="modal left">
  <div class="modal-dialog modal-lg w-100">
    <div class="modal-content">
	    ...
    </div>
  </div>
</div>
```



## License

GNU GENERAL PUBLIC LICENSE

Version 3, 29 June 2007