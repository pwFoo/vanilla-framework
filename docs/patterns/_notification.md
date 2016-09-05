---
collection: patterns
title: Notification
---

## .p-notification

Notifications are used to display global information. A notification will display at the top and fill the full width of the page. A notification can be a default, warning, negative or position.

```html
<div class="p-notification">
    <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
</div>
```

<div class="pl__relative" style="min-height: 120px;">
    <div class="p-notification">
        <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
    </div>
</div>

## .p-notification--warning

This warning variant should be used to convey information that is not critical but the user should be aware of.

```html
<div class="p-notification--warning">
    <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
</div>
```

<div class="pl__relative" style="min-height: 120px;">
    <div class="p-notification--warning">
        <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
    </div>
</div>

## .p-notification--negative

This negative variant should be used to convey information that is critical and the user should take action.

```html
<div class="p-notification--negative">
    <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
</div>
```

<div class="pl__relative" style="min-height: 120px;">
    <div class="p-notification--negative">
        <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
    </div>
</div>

## .p-notification--positive

This positive variant should be used to convey information of success or completion.

```html
<div class="p-notification--positive">
    <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
</div>
```

<div class="pl__relative" style="min-height: 120px;">
    <div class="p-notification--positive">
        <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
    </div>
</div>

### Adding actions

Notifications have the ability to add an action link or button to them. These will appear on the top right and stack below the message on small screens.

Note: All functionallity must be developed in independently.

```html
<div class="p-notification">
    <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
    <a href="#" class="p-notification__action">Change password</a>
</div>
```

<div class="pl__relative" style="min-height: 120px;">
    <div class="p-notification">
        <p class="p-notification__content">Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
        <a href="#" class="p-notification__action">Change password</a>
    </div>
</div>