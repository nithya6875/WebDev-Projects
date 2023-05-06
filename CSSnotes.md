## CSS Notes

# CSS Display

<p>There are a total of 12 display options in CSS</p>

1. block option

```
selector {
  display: inline-block;
  }
```
2. inline option

In HTML, the following tags have an inline display by default:

- `<a>`: Used for creating hyperlinks.
- `<abbr>`: Used for abbreviations or acronyms.
- `<b>`: Used for bold text.
- `<span>`: Used for grouping inline elements.
- `<button>`: Used for creating buttons.
- `<cite>`: Used for citing sources.
- `<code>`: Used for displaying code snippets.
- `<em>`: Used for emphasizing text.
- `<i>`: Used for italic text.
- `<img>`: Used for displaying images.
- `<input>`: Used for creating form elements such as text fields, checkboxes, and radio buttons.
- `<label>`: Used for labeling form elements.
- `<q>`: Used for short quotations.
- `<small>`: Used for small text.
- `<strong>`: Used for strongly emphasized text.
- `<sub>`: Used for subscript text.
- `<sup>`: Used for superscript text.
- `<textarea>`: Used for creating a multi-line text input.

It's important to note that the display value of an element can be changed using CSS. So, even if a tag has an inline display by default, it can be changed to a block or other display type using CSS.


4. inline-block option
5. flex option
6. grid option
7. table option
8. none option
9. list-item option
10. run-in
11. initial
12. inherit
13. unset


## Float property

Used to wrap around text around elements. The element is floated to the given direction and the rest of the elementd end up wrapping around the element.

Ways to acheive responsiveness in websites
1. ## Media Queries
There exists a media type in media queries which specifies to the devices the media query applies to.
```
@media screen and (max-width: 600px) {
  /* Styles go here */
}
```
Different media types that can be used with media queries - 
In CSS, media types are used to define the category of device that is used to display a web page. Different types of media can have different display capabilities and characteristics, so it is important to use appropriate styles for each media type.

Here are the different media types in CSS:

1. all: This is the default media type that applies to all devices.

2. screen: This media type is used for devices with a screen, such as desktop computers, laptops, and mobile devices.

3. print: This media type is used for printing devices such as printers or PDF generators.

4. speech: This media type is used for devices that use a text-to-speech synthesizer to read out the content of a web page, such as screen readers for visually impaired users.

5. handheld: This media type is used for small handheld devices, such as smartphones and PDAs.

6. projection: This media type is used for projection devices such as projectors.

7. braille: This media type is used for devices that render content in braille, such as refreshable braille displays.

8. tty: This media type is used for devices that display content using a fixed-width font, such as teletype machines.

By using different media types in CSS, you can ensure that your web page is optimized for different types of devices and users, making it more accessible and user-friendly.

Different expressions that can be used -
Width and height: These media features allow you to target specific screen sizes. For example, you can use the `min-width` and `max-width` features to apply styles to devices with a screen width that is greater than or less than a certain value.

Orientation: This feature allows you to target devices that are in either portrait or landscape orientation.

Resolution: This feature allows you to target devices with different display resolutions. For example, you can use the `min-resolution` and `max-resolution` features to apply styles to devices with a resolution that is greater than or less than a certain value.

Aspect ratio: This feature allows you to target devices with a specific aspect ratio, such as 16:9 or 4:3.

Color: This feature allows you to target devices with different color capabilities. For example, you can use the `color` and `color-index` features to apply styles to devices with a certain number of colors.

2. ## Flexbox

3. ## Grid
4. ## External Frameworks - Bootstrap


