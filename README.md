# A Cat Face custom element

## Usage

To embed the whole Cat Face series starting from episode one, just drop in the
element:

    <cat-face></cat-face>

### Choosing an episode

Setting the `episode` attribute on the element will start from that episode in
the series:

    <!-- Start from episode 12 of the series -->
    <cat-face episode="12"></cat-face>

### Setting the height/width

The `height` and `width` attributes dictate the dimensions of the Cat Face
video. Defaults: 360 and 640, respectively.

    <!-- Make the video gloriously big -->
    <cat-face width="1280" height="720"></cat-face>
