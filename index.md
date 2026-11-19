---
title: Linocut documentation
layout: default
---

# Linocut documentation

* TOC
{:toc}

## 1. Before you start

Linocut is made for galleries, print publishers and artists who sell prints. Everything it shows at scale is read from your products, so a few habits make it work:

- **Name sizes in the size option.** Write each value as a size: `30 × 40 cm`, `50x70 cm`, `18 x 24 in` or `A3`. The theme reads width, height and unit from the name. A value it cannot read (for example `Small`) is shown without scale.
- **Name frames in the frame option.** Values such as `Black`, `Natural oak`, `White`, `Walnut` or `Print only` are recognised by name: Linocut picks the frame color and the photographed moulding from it. A value containing `Print only`, `Unframed` or `No frame` is shown without a frame.
- **Use the artwork itself as the first product image**, flat and uncropped. Room photos and details can follow.
- **For room photos**, use a picture taken straight on, with an empty wall and a piece of furniture whose width you know.

Option names are set in **Theme settings > Wall view** (`Size, Format` and `Frame` by default).

## 2. Theme settings

Open **Online Store > Themes > Customize > Theme settings**.

| Group | What to set |
|---|---|
| Colors | Color schemes. Each section lets you choose one. **Edition status dot** colors the dot next to a sold-out or nearly sold-out edition. |
| Typography | Font, from the Shopify font library, and text size. |
| **Wall view** | Size and frame option names, the unit used when a size has none, and up to **three room photos** (see section 3). |
| **Frame photos** | Close-ups of your own frames for **The frame** view (see section 4). |
| Social media | Your accounts, shown as icons in the footer. Empty fields are not shown. |
| Cart | Drawer or page, and the order note. |
| Search | The heading of collections in search suggestions (Artists by default). |
| Layout | Page width. |
| Brand | Logo, logo width, favicon. |

## 3. The wall: real rooms, real scale

On every artwork page, the work hangs at its real size. Without a room photo, Linocut draws a plain wall with a two-metre sofa or a chair. With room photos, it hangs the work in your photos.

In **Theme settings > Wall view**, for each room:

1. **Room photo**: a straight-on photo with an empty wall.
2. **Room name**: shown on the buttons when shoppers can switch rooms (Living room, Hallway, Bedroom…).
3. **Width of the wall in the photo**: the real width, in centimeters, of what the photo shows at wall level. To find it, take a piece of furniture against the wall: if your 200 cm sofa covers 60 % of the photo's width, the wall shown is 200 ÷ 0.6 ≈ 335 cm.
4. **Hanging point, across**: where the center of the work goes, in % of the photo's width.
5. **Lowest edge of the frame, from the top**: the line works hang above, in % of the photo's height, so a large size never covers the furniture.
6. **Width of the furniture under the works**: used by **Compare sizes** to suggest a size.

The first room is also used on the home page hang, on artist pages and behind the framed photo of each work.

## 4. Frames

- **Moulding**: Linocut ships with photographed black, natural oak, white and walnut mouldings, chosen from the frame's name. Other names use a plain color, read from the name or from the option's swatch.
- **Mount**: every framed work gets a 5 cm white mount inside a 2 cm frame, on the wall, in the collection and in the cart.
- **The frame view**: in **Theme settings > Frame photos**, add a close-up of each of your frames and give it exactly the name used in the frame option (for example `Natural oak`). The artwork page then shows **The frame** view for that frame. Without a photo, the view is not shown: Linocut never presents its bundled mouldings as your frames.

## 5. The artwork page

The **Artwork** section has these blocks: Artist, Title, Price, Size and frame, Buy buttons, Description, **Edition and provenance**, Collapsible row, Text, Custom Liquid, and app blocks.

Views under the image, in this order:

- **On the wall**: the work at its real size in your room, in the chosen size and frame. **Compare sizes** outlines the other sizes around it and names the one closest to two thirds of the furniture below.
- **On your wall**: shoppers take a photo of their own wall, lay a measuring line on something they know the width of (a door, a sofa) and drag the work where they want it. The photo stays on their device; nothing is sent.
- **The frame**: your close-up of the chosen frame (section 4).
- Your product photos, videos and 3D models. The artwork's own photo is shown framed as chosen.

Section settings worth knowing:

- **Open on the middle size, framed**: the page opens on the middle size in the first frame, so the wall shows the work as it would hang.
- **Let shoppers try a work on their own wall** turns **On your wall** on or off.
- **Keep the buy button in reach on phones** shows a buy bar once the shopper scrolls past the views.

**Edition and provenance** is a gallery label: edition, technique, paper, how the print is made, and an optional certificate line. Each field can be connected to a metafield. **Show copies left below** shows "Only N copies left" from your real inventory, only when Shopify tracks it.

## 6. The cart wall

The cart page hangs every framed work of the cart together, at its real size and in its own frame, on one centre line in your first room photo. Changing a size or a frame in the cart redraws the wall. Nothing is kept outside Shopify's cart: there is no separate list to manage.

## 7. Collections and artists

- **True format / To scale**: a switch above every collection. **To scale** shows each work at the height of its smallest size, against the tallest one on the page.
- **Three sizes in the to-scale view** (Collection section): the switch offers the small, middle and large printed sizes (for example 50, 70 and 100 cm), and every work redraws at that size, against the largest one. Made for poster shops.
- **Layout > Museum room** (Collection section): the works hang side by side on one long wall, framed in the **Frame in the museum room**, at their relative sizes, with their label underneath.
- **Show works framed** draws each work in its mount and in the color of its first frame (collection, search results, recommendations, featured collection).
- **Filters** come from the **Search & Discovery** app: add Size, Frame or Artist filters there.
- **Artist pages**: for a collection per artist, choose the template **collection.artist**. The **Artist header** section shows the collection's title and description, then a few of the artist's works hung at their real size.
- **Collections list**: choose which collections to show (for example only your artists) in the section's **Collections** setting.

## 8. Home page

Sections made for Linocut: **Hang** (works from a collection hung at their real size in your room), **Artist index**, **Featured collection**, **Featured work**, **Shop by format** (each size drawn at its relative size, optionally with a chosen work in its frame), **Journal and signup**, **Image with text**, **Rich text**, **Announcement**, **Custom Liquid**.

For a museum of paintings (style Cabinet):

- **Room of the month**: one work, very large, in your room, with its painter, original size and collection beside it.
- **Rooms**: one door per collection (for example Portraits, Landscapes), each showing three of its works framed.
- **Timeline**: works placed on one line at their year, from the earliest to the latest. Add one block per work, with its year.
- **Detail**: one work enlarged on a fragment you choose (**Zoom**, horizontal and vertical focus), with a few lines of text.

For a poster shop (style Ultramarine):

- **Poster wall**: the works of a collection framed side by side, each at the real size of one of its prints, sizes mixed or all the same.
- **Shop by colour**: one chip per colour you choose, each opening a collection (for example an automated collection of the works tagged with that colour).
- **Pairs and trios**: groups of two or three works you choose, hung together in your room, with one button that adds the whole group to the cart in the size and frame shown.
- **Collection tiles**: one large square per collection (movements, series, themes).

On the artwork page, two blocks go with these styles: **Museum label** (artist, dates, title, medium, collection and wall text, each connectable to a metafield) and **Colours in the work** (five colours read from the image, to match a room).

## 9. Journal, articles, 404 and password

**Journal** (blog template), setting **Layout**:

- **Plate of framed covers**: each article image framed at its own proportions, never cropped.
- **Guide by room (tags)**: articles grouped by blog tag, in the order you write in **Rooms, in order** (for example `Portraits, Landscapes`); articles without one of these tags are grouped under **Notes without a room**.
- **Colour cards**: each card takes the main colour of its image, with text that stays readable.

**Article**: works you link to in the text (a normal link to a product page) are hung after the article, with no other setting. **Works in the text** chooses how: hung at their sizes with prices, labels in the margin then a room, or posters with one button that adds them all. **Head > Title beside the image, with its colours** shows the five colours of the article image under the title.

**Page not found**, setting **Layout**: an empty frame in your room, a closed museum room with the doors of the **Collections** you choose, or a blank wall with three empty frames at 50, 70 and 100 cm.

**Password page**, setting **Layout**: a photo beside the text, an opening-night card with a framed work, a date and time, or a large poster with three frame sizes.

## 10. Styles

Linocut comes with three styles, each made for a different way of selling art: **Linocut** (prints and photographs, warm white), **Cabinet** (paintings, in museum rooms, aubergine walls) and **Ultramarine** (posters, by colour and size, ultramarine blue). Each style installs its own home page, collection, artwork page, journal, article, 404 and password page; every section can be used in any style.

## 11. Languages

- The storefront is translated into English, French, Italian, German and Spanish.
- The theme editor is available in the same five languages.
- Your own content (products, pages, section texts) is translated with Shopify's **Translate & Adapt** app.

## 12. FAQ

**A work shows "Shown without scale".** Its size option value has no readable size. Rename the value, for example `40 × 50 cm`, and check the option name is listed in **Theme settings > Wall view > Size option names**.

**The frame is a plain color instead of wood.** Only black, natural oak, white and walnut have a photographed moulding. Other frames use their color: set the option's swatch, or include a color word in the name.

**The work covers the sofa in my room photo.** Lower the line in **Lowest edge of the frame, from the top** (a smaller percentage) for that room.

**Sizes look too large or too small in my room.** Check **Width of the wall in the photo**: measure a known piece of furniture in the photo again (section 3).

**Where is the shopper's wall photo stored?** In their browser only, for the visit. Linocut never uploads it.

**Can I show limited editions?** Yes: write it in **Edition and provenance**, and track inventory in Shopify so "copies left" is real. Linocut never invents stock or urgency.

**Is Linocut fast?** On our three demo stores, Lighthouse gives 100 for accessibility on every page measured, and 71 to 99 for performance (home, artwork, collection, journal and article pages, phone and computer, 18 Nov. 2026).

**How do I show the works mentioned in an article?** Link to them in the text, like any link to a product page. Linocut finds the links and hangs the works after the article, twelve at most.

Need more help? [Contact support]({{ '/support/' | relative_url }}).
