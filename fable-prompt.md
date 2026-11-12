I've attached photos of my church, Hope Lutheran Church in Sunbury, Ohio: several of the sanctuary interior and a few of the exterior. Build me an interactive 3D model of the sanctuary that I can walk through. I want to try redesign options that would make it more reverent and "high church" and see what each option would roughly cost.

## Deliverable
Make a single self-contained HTML file using Three.js (pinned version from a CDN) that runs in a desktop browser with no build step. It should have:
1. **A 3D walkthrough.** Use first-person WASD + mouse-look at standing eye height (about 5'6"). Add an orbit/"dollhouse" view and preset camera spots: rear entrance, center aisle at the font, a pew seat in the middle of the room, the chancel looking back at the congregation, and the pulpit.
2. **An options panel.** Group options by category (listed below). Every selection should update the 3D scene live.
3. **A live cost estimator.** For each choice, show the quantity (computed from the room geometry), the unit, a low and high installed unit cost, and a low–high line total. Also show a running grand total with a contingency line (default 15%, adjustable) and a design/permits line. Label all prices as rough 2026 Central Ohio ballparks, not quotes.
4. **Before/After.** Add a one-click toggle back to the current "as-is" sanctuary.
5. **Saved schemes.** Let me save named combinations (e.g. "Modest refresh", "Full high-church"), compare two side by side by cost, and export a printable summary of the selections with the itemized costs.
6. **An editable dimensions panel.** All geometry should be parametric so I can enter real tape-measured dimensions and have the model and the quantities update. The dimensions below are estimates from photos.

## The existing sanctuary (model this faithfully as the "as-is" baseline)
- **Room:** a single rectangular nave with no separate chancel apse. Rough estimate: 48–52 ft wide, 65–75 ft deep, side walls about 10 ft tall, and a low-pitch gable ceiling peaking around 18–20 ft. The ridge runs front-to-back toward the chancel.
- **Ceiling:** white textured drywall (popcorn/knockdown) following the gable. It holds white ceiling fans, many white twin-head track/spot fixtures, white box speakers, and two ceiling-mounted projectors on drop poles.
- **Side walls:** flat cream/ivory painted drywall. Along the top of each side wall is a stained pine/cedar fascia beam with cove uplighting washing up onto the ceiling. There are wooden Gothic-arch hymn number boards on both side walls. The right wall has glass doors/windows to the outside with wood trim. There are doors at the rear left and a lit EXIT sign.
- **Chancel (front) wall:** a gable wall with four stained glass panels set high in the gable. The two center panels are tall and the two outer ones are shorter, with angled tops following the roofline. They are framed by vertical stained-wood posts that run down to the floor. The glass is colorful and folk-art style. From left to right:
  - an angel/shepherds with a star
  - Christ in a red robe holding a lamb (Good Shepherd)
  - Christ in a red robe with arms raised under a radiant sunburst halo
  - three crosses on a hill (Calvary)
- **Below the glass:** a cream wall with a plain stained-wood Latin cross centered and a hanging red sanctuary lamp. Seasonal fabric banners hang between the posts on either side of the cross. Two flush wood doors lead to the sacristy/side rooms left and right of center.
- **Chancel platform:** about 2 carpeted steps up, in the same carpet or a mauve/purple tone. It holds:
  - a light pine freestanding altar table with paraments (green in Ordinary Time)
  - two candlesticks
  - a light pine pulpit/ambo with a hanging parament, front right
  - a wooden high-back presider chair, right
  - a piano/organ under a white cover, front left
  - an American flag front left and a Christian flag front right
- **Projection:** two pull-down projection screens hang just outside the chancel posts, left and right of the stained glass area.
- **Font:** an octagonal light-oak baptismal font with a brass cross on the lid stands in the center aisle toward the rear.
- **Seating:** navy blue upholstered stacking banquet chairs with black metal frames and fabric book pockets on the back holding red hymnals. They are set in two sections with a center aisle, roughly 12–14 rows per side and about 8 chairs per row. Make chair count a parameter.
- **Floor:** wall-to-wall gray/taupe commercial carpet throughout.
- **Lighting character:** fairly flat and bright. The overhead track spots and cove uplighting give it a fellowship-hall feel.
- **Exterior (optional low-detail context, or a "step outside" view):**
  - gray-blue horizontal lap siding with white trim
  - a tall front gable with an open white timber-frame portico over the entrance and a "WELCOME" sign over the double doors
  - a white steeple with a gold cross
  - a single-story wing to the left
  - a circular asphalt drive around a lawn island with a large iron anchor sculpture

## Redesign option categories
Each option needs its own 3D look and its own cost line. Always include "Keep as-is ($0)".

**Flooring** (allow separate choices for the seating area, the center aisle, and the chancel):
- new carpet
- luxury vinyl plank
- oak hardwood
- porcelain tile in a stone look
- natural slate or limestone
- marble/porcelain checkerboard (for the aisle)
- terrazzo
- a contrasting tile runner down the center aisle with carpet under the seating

**Chancel and altar:**
- raise and extend the platform
- add an oak or wrought-iron communion rail with kneeling cushion
- move the altar against the east wall with a carved wood reredos or a dossal curtain with a baldachin/tester
- replace the Latin cross with a crucifix
- six altar candlesticks
- an altar frontal
- an elevated pulpit with a sounding board
- a separate lectern
- a credence table
- remove or relocate the flags

**Walls:**
- new paint palette (deep colors such as oxblood, Marian blue, or sage, with gilt accents)
- oak wainscoting/paneling to 4 ft or 7 ft
- stone veneer on the chancel wall only, or on all walls
- limestone-look panels
- stenciled borders
- 14 Stations of the Cross plaques
- framed icons or a painted mural on the chancel wall
- improved hymn boards

**Ceiling:**
- remove the popcorn texture and paint
- tongue-and-groove wood ceiling
- decorative faux timber scissor trusses or hammer-beam style trusses
- coffered panels
- deep blue "heavens" ceiling with gold stars over the chancel
- remove the fans and track lights

**Lighting:**
- Gothic lantern pendants or iron chandeliers in place of the track spots
- keep or remove the cove lighting
- warm dimmable scenes
- accent lighting on the altar and cross
- keep or replace the sanctuary lamp

**Stained glass:**
- keep the existing panels
- restore/re-lead them
- replace them with traditional figural Gothic-style glass (themes such as the Crucifixion, Christ the King, the Evangelists, or Luther's Rose)
- add new stained glass on the side-wall windows
- add a rose/round window

**Projection:**
- keep both screens
- motorized screens that retract fully into a ceiling soffit
- a single smaller screen
- remove the screens entirely and use printed bulletins/hymnals and hymn boards
- discreet flat panels on the side walls only

**Seating:**
- reupholster/replace the stacking chairs in a burgundy or tan fabric
- wood chapel chairs with kneelers
- new solid oak pews with or without kneelers and hymnal racks
- refurbished used pews
- seat count should stay roughly constant or show the change

**Font and other furnishings:**
- relocate the font to the entrance
- replace it with a stone or larger octagonal oak font
- a processional cross and torches
- a paschal candle stand
- a narthex screen or a rood-style beam with crucifix over the chancel step

**Doors, windows and architectural details:**
- replace the flush sacristy/side doors with paneled oak doors in Gothic or round-arch frames
- reshape the side-wall window and door openings with lancet-arch trim
- add wood columns or engaged pilasters along the side walls to suggest aisles/bays
- an arched chancel opening or a proscenium-style frame around the chancel
- crown and base moldings

**Music and acoustics:**
- a digital organ with a visible façade of decorative pipes, or a real pipe organ (show it as a high-cost option)
- move the organ/piano and add a choir area to one side of the chancel or at the rear
- a small rear choir/organ loft (flag that it needs structural work)
- hide the box speakers in column-style line arrays or paint them to match
- an acoustics note: harder surfaces (tile, stone, wood ceiling) liven the room for chant and hymn singing. Show a rough estimated reverb effect (e.g. "drier / balanced / live") for the selected surfaces next to the cost.

**Devotional and liturgical additions:**
- a votive candle stand
- a memorial/prayer corner with an icon
- permanent embroidered dossal and frontals in place of seasonal vinyl banners
- a church-year toggle that switches paraments and banners between the liturgical colors (white, green, violet, blue, red, black)
- a bell or sanctus bell
- an aumbry or a wall niche for sacred vessels

**Entrance and narthex:**
- a defined narthex area at the rear, using a wood screen with glass or a half wall
- a stone or tile floor at the entry
- a holy water/font area at the door
- a welcome table and bulletin rack moved out of the worship space

**Layout:**
- widen the center aisle for processions
- add side aisles
- choir-style (antiphonal) seating as an alternative arrangement
- adjust the number of rows and the spacing, showing the seat count each time

**Mechanical/cleanup:**
- replace the ceiling fans with hidden HVAC destratification
- relocate or conceal the projectors
- low-profile exit signage
- conceal the cabling

**Anything else:** These lists are a starting point, not a limit. Use your own knowledge of traditional Lutheran and liturgical church architecture to add other options that would make the space more reverent. Add each one to the most fitting category, or create a new category, with its own 3D look and cost line.

## Cost guidance
Store all cost data in one clearly marked, editable JS object so I can correct prices as real quotes come in. Compute quantities from the geometry (floor sq ft per zone, wall sq ft minus openings, ceiling sq ft along the slope, linear feet of pews and rail, number of windows and stained glass sq ft). Use these rough installed ranges as starting anchors, adjust them with your own knowledge, and note any assumption you change:
- **Flooring (per sq ft installed):** carpet $4–9, LVP $5–10, oak hardwood $10–20, porcelain tile $12–25, natural stone $25–50, terrazzo $30–60. Also add carpet removal and subfloor prep.
- **Stone veneer:** $25–55/sf. Oak wainscoting: $40–90/linear ft.
- **Ceiling:** popcorn removal + paint $3–6/sf. T&G wood ceiling $15–30/sf. Faux timber trusses/beams $150–400/lf.
- **New custom stained glass:** $150–400/sf. Restoration: $50–150/sf.
- **Pews:** new oak $150–350 per linear ft, add $40–80/ft for kneelers, used/refurbished $50–150/ft. Chapel chairs: $150–400 each.
- **Communion rail:** $300–900/lf. Reredos/dossal: $5k–60k depending on scope.
- **Lighting:** pendants/chandeliers $800–4,000 each installed.
- **Screens:** motorized recessed screens with a soffit $3k–10k each. Removal is minimal cost.
- **Organs:** a digital organ with a decorative pipe façade $40k–150k. A pipe organ $300k–1M+ (new) or less if relocated/used.
- **Doors and paneling:** paneled oak doors $2.5k–7k each installed. A narthex screen/half wall $10k–45k.
- **Embroidered textiles:** a dossal/frontal set $2k–10k per liturgical color.

Show the total, a per-category subtotal, and a "cost per seat" figure. Include a short visible disclaimer that these are planning estimates only and that real bids, architect/structural review (especially for trusses, stone weight, and raising the chancel), and permits are required.

## Quality bar
- Make the as-is model clearly recognizable against my photos: proportions, the four-panel glass gable with wood posts, the cross, the chancel layout, the blue chairs, and the cove-lit side beams. Use procedural textures and materials (no external image assets required). Approximate the stained glass panels with emissive colored geometry or canvas-drawn textures that suggest each scene.
- Use warm, believable lighting, and let light through the stained glass glow. Keep performance smooth on a normal laptop by using instancing for chairs and pews.
- Keep the UI clean: a collapsible side panel with options and a bottom bar with the live total.
- Before you finish, check that every option actually changes the scene and the cost table, and that changing a room dimension updates the quantities.
