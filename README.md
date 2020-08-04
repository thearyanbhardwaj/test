# test
Hi Wordpres.org
contact info@aryabbhardwaj.com
/*! This file is auto-generated */
/*
 * Button mixin- creates a button effect with correct
 * highlights/shadows, based on a base color.
 */
body {
  background: #f1f1f1;
}

/* Links */
a {
  color: #0073aa;
}

a:hover, a:active, a:focus {
  color: #0096dd;
}

#post-body .misc-pub-post-status:before,
#post-body #visibility:before,
.curtime #timestamp:before,
#post-body .misc-pub-revisions:before,
span.wp-media-buttons-icon:before {
  color: currentColor;
}

/* Forms */
input[type=checkbox]:checked::before {
  content: url("data:image/svg+xml;utf8,%3Csvg%20xmlns%3D%27http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%27%20viewBox%3D%270%200%2020%2020%27%3E%3Cpath%20d%3D%27M14.83%204.89l1.34.94-5.81%208.38H9.02L5.78%209.67l1.34-1.25%202.57%202.4z%27%20fill%3D%27%237e8993%27%2F%3E%3C%2Fsvg%3E");
}

input[type=radio]:checked::before {
  background: #7e8993;
}

.wp-core-ui input[type="reset"]:hover,
.wp-core-ui input[type="reset"]:active {
  color: #0096dd;
}

input[type="text"]:focus,
input[type="password"]:focus,
input[type="color"]:focus,
input[type="date"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="email"]:focus,
input[type="month"]:focus,
input[type="number"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="text"]:focus,
input[type="time"]:focus,
input[type="url"]:focus,
input[type="week"]:focus,
input[type="checkbox"]:focus,
input[type="radio"]:focus,
select:focus,
textarea:focus {
  border-color: #096484;
  box-shadow: 0 0 0 1px #096484;
}

/* Core UI */
.wp-core-ui .button {
  border-color: #7e8993;
  color: #32373c;
}

.wp-core-ui .button.hover,
.wp-core-ui .button:hover,
.wp-core-ui .button.focus,
.wp-core-ui .button:focus {
  border-color: #717c87;
  color: #262a2e;
}

.wp-core-ui .button.focus,
.wp-core-ui .button:focus {
  border-color: #7e8993;
  color: #262a2e;
  box-shadow: 0 0 0 1px #32373c;
}

.wp-core-ui .button:active {
  border-color: #7e8993;
  color: #262a2e;
  box-shadow: none;
}

.wp-core-ui .button.active,
.wp-core-ui .button.active:focus,
.wp-core-ui .button.active:hover {
  border-color: #e1a948;
  color: #262a2e;
  box-shadow: inset 0 2px 5px -3px #e1a948;
}

.wp-core-ui .button.active:focus {
  box-shadow: 0 0 0 1px #32373c;
}

.wp-core-ui .button-primary {
  background: #e1a948;
  border-color: #e1a948;
  color: #fff;
}

.wp-core-ui .button-primary:hover, .wp-core-ui .button-primary:focus {
  background: #e3af55;
  border-color: #dfa33b;
  color: #fff;
}

.wp-core-ui .button-primary:focus {
  box-shadow: 0 0 0 1px #fff, 0 0 0 3px #e1a948;
}

.wp-core-ui .button-primary:active {
  background: #dd9f32;
  border-color: #dd9f32;
  color: #fff;
}

.wp-core-ui .button-primary.active, .wp-core-ui .button-primary.active:focus, .wp-core-ui .button-primary.active:hover {
  background: #e1a948;
  color: #fff;
  border-color: #bd831f;
  box-shadow: inset 0 2px 5px -3px #241906;
}

.wp-core-ui .button-primary[disabled], .wp-core-ui .button-primary:disabled, .wp-core-ui .button-primary.button-primary-disabled, .wp-core-ui .button-primary.disabled {
  color: #d1cdc7 !important;
  background: #db9925 !important;
  border-color: #db9925 !important;
  text-shadow: none !important;
}

.wp-core-ui .button-group > .button.active {
  border-color: #e1a948;
}

.wp-core-ui .wp-ui-primary {
  color: #fff;
  background-color: #52accc;
}

.wp-core-ui .wp-ui-text-primary {
  color: #52accc;
}

.wp-core-ui .wp-ui-highlight {
  color: #fff;
  background-color: #096484;
}

.wp-core-ui .wp-ui-text-highlight {
  color: #096484;
}

.wp-core-ui .wp-ui-notification {
  color: #fff;
  background-color: #e1a948;
}

.wp-core-ui .wp-ui-text-notification {
  color: #e1a948;
}

.wp-core-ui .wp-ui-text-icon {
  color: #e5f8ff;
}

/* List tables */
.wrap .add-new-h2:hover,
.wrap .page-title-action:hover {
  color: #fff;
  background-color: #52accc;
}

.view-switch a.current:before {
  color: #52accc;
}

.view-switch a:hover:before {
  color: #e1a948;
}

/* Admin Menu */
#adminmenuback,
#adminmenuwrap,
#adminmenu {
  background: #52accc;
}

#adminmenu a {
  color: #fff;
}

#adminmenu div.wp-menu-image:before {
  color: #e5f8ff;
}

#adminmenu a:hover,
#adminmenu li.menu-top:hover,
#adminmenu li.opensub > a.menu-top,
#adminmenu li > a.menu-top:focus {
  color: #fff;
  background-color: #096484;
}

#adminmenu li.menu-top:hover div.wp-menu-image:before,
#adminmenu li.opensub > a.menu-top div.wp-menu-image:before {
  color: #fff;
}

/* Active tabs use a bottom border color that matches the page background color. */
.about-wrap .nav-tab-active,
.nav-tab-active,
.nav-tab-active:hover {
  background-color: #f1f1f1;
  border-bottom-color: #f1f1f1;
}

/* Admin Menu: submenu */
#adminmenu .wp-submenu,
#adminmenu .wp-has-current-submenu .wp-submenu,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu,
.folded #adminmenu .wp-has-current-submenu .wp-submenu,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu {
  background: #4796b3;
}

#adminmenu li.wp-has-submenu.wp-not-current-submenu.opensub:hover:after {
  border-right-color: #4796b3;
}

#adminmenu .wp-submenu .wp-submenu-head {
  color: #e2ecf1;
}

#adminmenu .wp-submenu a,
#adminmenu .wp-has-current-submenu .wp-submenu a,
.folded #adminmenu .wp-has-current-submenu .wp-submenu a,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu a,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu a {
  color: #e2ecf1;
}

#adminmenu .wp-submenu a:focus, #adminmenu .wp-submenu a:hover,
#adminmenu .wp-has-current-submenu .wp-submenu a:focus,
#adminmenu .wp-has-current-submenu .wp-submenu a:hover,
.folded #adminmenu .wp-has-current-submenu .wp-submenu a:focus,
.folded #adminmenu .wp-has-current-submenu .wp-submenu a:hover,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu a:focus,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu a:hover,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu a:focus,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu a:hover {
  color: #fff;
}

/* Admin Menu: current */
#adminmenu .wp-submenu li.current a,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu li.current a,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu li.current a {
  color: #fff;
}

#adminmenu .wp-submenu li.current a:hover, #adminmenu .wp-submenu li.current a:focus,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu li.current a:hover,
#adminmenu a.wp-has-current-submenu:focus + .wp-submenu li.current a:focus,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu li.current a:hover,
#adminmenu .wp-has-current-submenu.opensub .wp-submenu li.current a:focus {
  color: #fff;
}

ul#adminmenu a.wp-has-current-submenu:after,
ul#adminmenu > li.current > a.current:after {
  border-right-color: #f1f1f1;
}

#adminmenu li.current a.menu-top,
#adminmenu li.wp-has-current-submenu a.wp-has-current-submenu,
#adminmenu li.wp-has-current-submenu .wp-submenu .wp-submenu-head,
.folded #adminmenu li.current.menu-top {
  color: #fff;
  background: #096484;
}

#adminmenu li.wp-has-current-submenu div.wp-menu-image:before,
#adminmenu a.current:hover div.wp-menu-image:before,
#adminmenu li.wp-has-current-submenu a:focus div.wp-menu-image:before,
#adminmenu li.wp-has-current-submenu.opensub div.wp-menu-image:before,
#adminmenu li:hover div.wp-menu-image:before,
#adminmenu li a:focus div.wp-menu-image:before,
#adminmenu li.opensub div.wp-menu-image:before,
.ie8 #adminmenu li.opensub div.wp-menu-image:before {
  color: #fff;
}

/* Admin Menu: bubble */
#adminmenu .awaiting-mod,
#adminmenu .update-plugins {
  color: #fff;
  background: #e1a948;
}

#adminmenu li.current a .awaiting-mod,
#adminmenu li a.wp-has-current-submenu .update-plugins,
#adminmenu li:hover a .awaiting-mod,
#adminmenu li.menu-top:hover > a .update-plugins {
  color: #fff;
  background: #4796b3;
}

/* Admin Menu: collapse button */
#collapse-button {
  color: #e5f8ff;
}

#collapse-button:hover,
#collapse-button:focus {
  color: #fff;
}

/* Admin Bar */
#wpadminbar {
  color: #fff;
  background: #52accc;
}

#wpadminbar .ab-item,
#wpadminbar a.ab-item,
#wpadminbar > #wp-toolbar span.ab-label,
#wpadminbar > #wp-toolbar span.noticon {
  color: #fff;
}

#wpadminbar .ab-icon,
#wpadminbar .ab-icon:before,
#wpadminbar .ab-item:before,
#wpadminbar .ab-item:after {
  color: #e5f8ff;
}

#wpadminbar:not(.mobile) .ab-top-menu > li:hover > .ab-item,
#wpadminbar:not(.mobile) .ab-top-menu > li > .ab-item:focus,
#wpadminbar.nojq .quicklinks .ab-top-menu > li > .ab-item:focus,
#wpadminbar.nojs .ab-top-menu > li.menupop:hover > .ab-item,
#wpadminbar .ab-top-menu > li.menupop.hover > .ab-item {
  color: #fff;
  background: #4796b3;
}

#wpadminbar:not(.mobile) > #wp-toolbar li:hover span.ab-label,
#wpadminbar:not(.mobile) > #wp-toolbar li.hover span.ab-label,
#wpadminbar:not(.mobile) > #wp-toolbar a:focus span.ab-label {
  color: #fff;
}

#wpadminbar:not(.mobile) li:hover .ab-icon:before,
#wpadminbar:not(.mobile) li:hover .ab-item:before,
#wpadminbar:not(.mobile) li:hover .ab-item:after,
#wpadminbar:not(.mobile) li:hover #adminbarsearch:before {
  color: #fff;
}

/* Admin Bar: submenu */
#wpadminbar .menupop .ab-sub-wrapper {
  background: #4796b3;
}

#wpadminbar .quicklinks .menupop ul.ab-sub-secondary,
#wpadminbar .quicklinks .menupop ul.ab-sub-secondary .ab-submenu {
  background: #74b6ce;
}

#wpadminbar .ab-submenu .ab-item,
#wpadminbar .quicklinks .menupop ul li a,
#wpadminbar .quicklinks .menupop.hover ul li a,
#wpadminbar.nojs .quicklinks .menupop:hover ul li a {
  color: #e2ecf1;
}

#wpadminbar .quicklinks li .blavatar,
#wpadminbar .menupop .menupop > .ab-item:before {
  color: #e5f8ff;
}

#wpadminbar .quicklinks .menupop ul li a:hover,
#wpadminbar .quicklinks .menupop ul li a:focus,
#wpadminbar .quicklinks .menupop ul li a:hover strong,
#wpadminbar .quicklinks .menupop ul li a:focus strong,
#wpadminbar .quicklinks .ab-sub-wrapper .menupop.hover > a,
#wpadminbar .quicklinks .menupop.hover ul li a:hover,
#wpadminbar .quicklinks .menupop.hover ul li a:focus,
#wpadminbar.nojs .quicklinks .menupop:hover ul li a:hover,
#wpadminbar.nojs .quicklinks .menupop:hover ul li a:focus,
#wpadminbar li:hover .ab-icon:before,
#wpadminbar li:hover .ab-item:before,
#wpadminbar li a:focus .ab-icon:before,
#wpadminbar li .ab-item:focus:before,
#wpadminbar li .ab-item:focus .ab-icon:before,
#wpadminbar li.hover .ab-icon:before,
#wpadminbar li.hover .ab-item:before,
#wpadminbar li:hover #adminbarsearch:before,
#wpadminbar li #adminbarsearch.adminbar-focused:before {
  color: #fff;
}

#wpadminbar .quicklinks li a:hover .blavatar,
#wpadminbar .quicklinks li a:focus .blavatar,
#wpadminbar .quicklinks .ab-sub-wrapper .menupop.hover > a .blavatar,
#wpadminbar .menupop .menupop > .ab-item:hover:before,
#wpadminbar.mobile .quicklinks .ab-icon:before,
#wpadminbar.mobile .quicklinks .ab-item:before {
  color: #fff;
}

#wpadminbar.mobile .quicklinks .hover .ab-icon:before,
#wpadminbar.mobile .quicklinks .hover .ab-item:before {
  color: #e5f8ff;
}

/* Admin Bar: search */
#wpadminbar #adminbarsearch:before {
  color: #e5f8ff;
}

#wpadminbar > #wp-toolbar > #wp-admin-bar-top-secondary > #wp-admin-bar-search #adminbarsearch input.adminbar-input:focus {
  color: #fff;
  background: #6eb9d4;
}

/* Admin Bar: recovery mode */
#wpadminbar #wp-admin-bar-recovery-mode {
  color: #fff;
  background-color: #e1a948;
}

#wpadminbar #wp-admin-bar-recovery-mode .ab-item,
#wpadminbar #wp-admin-bar-recovery-mode a.ab-item {
  color: #fff;
}

#wpadminbar .ab-top-menu > #wp-admin-bar-recovery-mode.hover > .ab-item,
#wpadminbar.nojq .quicklinks .ab-top-menu > #wp-admin-bar-recovery-mode > .ab-item:focus,
#wpadminbar:not(.mobile) .ab-top-menu > #wp-admin-bar-recovery-mode:hover > .ab-item,
#wpadminbar:not(.mobile) .ab-top-menu > #wp-admin-bar-recovery-mode > .ab-item:focus {
  color: #fff;
  background-color: #cb9841;
}

/* Admin Bar: my account */
#wpadminbar .quicklinks li#wp-admin-bar-my-account.with-avatar > a img {
  border-color: #6eb9d4;
  background-color: #6eb9d4;
}

#wpadminbar #wp-admin-bar-user-info .display-name {
  color: #fff;
}

#wpadminbar #wp-admin-bar-user-info a:hover .display-name {
  color: #fff;
}

#wpadminbar #wp-admin-bar-user-info .username {
  color: #e2ecf1;
}

/* Pointers */
.wp-pointer .wp-pointer-content h3 {
  background-color: #096484;
  border-color: #07526c;
}

.wp-pointer .wp-pointer-content h3:before {
  color: #096484;
}

.wp-pointer.wp-pointer-top .wp-pointer-arrow,
.wp-pointer.wp-pointer-top .wp-pointer-arrow-inner,
.wp-pointer.wp-pointer-undefined .wp-pointer-arrow,
.wp-pointer.wp-pointer-undefined .wp-pointer-arrow-inner {
  border-bottom-color: #096484;
}

/* Media */
.media-item .bar,
.media-progress-bar div {
  background-color: #096484;
}

.details.attachment {
  box-shadow: inset 0 0 0 3px #fff, inset 0 0 0 7px #096484;
}

.attachment.details .check {
  background-color: #096484;
  box-shadow: 0 0 0 1px #fff, 0 0 0 2px #096484;
}

.media-selection .attachment.selection.details .thumbnail {
  box-shadow: 0 0 0 1px #fff, 0 0 0 3px #096484;
}

/* Themes */
.theme-browser .theme.active .theme-name,
.theme-browser .theme.add-new-theme a:hover:after,
.theme-browser .theme.add-new-theme a:focus:after {
  background: #096484;
}

.theme-browser .theme.add-new-theme a:hover span:after,
.theme-browser .theme.add-new-theme a:focus span:after {
  color: #096484;
}

.theme-section.current,
.theme-filter.current {
  border-bottom-color: #52accc;
}

body.more-filters-opened .more-filters {
  color: #fff;
  background-color: #52accc;
}

body.more-filters-opened .more-filters:before {
  color: #fff;
}

body.more-filters-opened .more-filters:hover,
body.more-filters-opened .more-filters:focus {
  background-color: #096484;
  color: #fff;
}

body.more-filters-opened .more-filters:hover:before,
body.more-filters-opened .more-filters:focus:before {
  color: #fff;
}

/* Widgets */
.widgets-chooser li.widgets-chooser-selected {
  background-color: #096484;
  color: #fff;
}

.widgets-chooser li.widgets-chooser-selected:before,
.widgets-chooser li.widgets-chooser-selected:focus:before {
  color: #fff;
}

/* Responsive Component */
div#wp-responsive-toggle a:before {
  color: #e5f8ff;
}

.wp-responsive-open div#wp-responsive-toggle a {
  border-color: transparent;
  background: #096484;
}

.wp-responsive-open #wpadminbar #wp-admin-bar-menu-toggle a {
  background: #4796b3;
}

.wp-responsive-open #wpadminbar #wp-admin-bar-menu-toggle .ab-icon:before {
  color: #e5f8ff;
}

/* TinyMCE */
.mce-container.mce-menu .mce-menu-item:hover,
.mce-container.mce-menu .mce-menu-item.mce-selected,
.mce-container.mce-menu .mce-menu-item:focus,
.mce-container.mce-menu .mce-menu-item-normal.mce-active,
.mce-container.mce-menu .mce-menu-item-preview.mce-active {
  background: #096484;
}
