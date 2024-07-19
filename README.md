
# Foxis JeeLink-clone

Funkmodul RFM69HCW
Gehaeuse BUD USB-7201-C

## Intro

JeeLinks are transceivers with a microcontroller, that can be
attached to the USB port of a PC. They were designed many
years ago by JeeLabs a.k.a. Jean-Claude Wippler, and like all
of the (many!) cool designs on his now sadly defunct weblog
under jeelabs.org, they were completely Open-Source-Hardware -
while there was a webshop where you could buy ready-made
JeeLinks if you were lazy, you could also just build them
yourself, or modify the designs.

I use many JeeLinks as receivers for my various "FoxTemp"
sensors like foxtemp2016 or foxtemp2024. For that, the
JeeLink is flashed with the "LaCrosse" sketch developed
by the FHEM project (with one minor source code modification
needed to adapt the settings) and attached to a PC, where
a little deamon makes the received data available for query
via network.

Unfortunately, by now jeelabs.org is completely defunct and
you can only access the treasure trove of information that used
to be hosted there through archive.org. The webshop is still
there, but it is in the UK - and thanks to Brexit, ordering
from there to mainland Europe promises to be so painful that
I want to avoid it at all cost.

So where do I get my JeeLinks now?
Well the plan is to do what I've been doing a lot recently:
Design a PCB with mostly SMD components on one side, and
send it off to china for fabrication. And you may ask,
"Wait, doesn't that have the same problems as ordering
from the UK?", and of course in both cases it means crossing
the border from outside the EU into the EU taxation and
customs union. The difference is that the chinese fab
is registered as a so called IOSS, Import One Stop Shop.
That means (as of July 2024) that for any orders below 150
Euro the shop will directly collect the applicable VAT
and transfer it to EU customs. As orders below 150 Euro
are exempt from taxes other than VAT, that means everything
has already been paid when your parcel enters the EU.
And that makes a huge difference, because most parcel services
massively rip you off with the tax handling. For example,
DHL Express will charge a "Kapitalbereitstellungs-
Provision" of (at least) a whopping 14.88 Euros, even if
there was just a single cent of VAT to be paid for the
import, for borrowing you the money for two days. It's
also not possible to opt out of their shitty disservice
and just collect the parcel yourself at the next customs
office. But if there is no VAT or other taxes to be
paid, your parcel just arrives without the ripoff.

Note that this is NOT a full JeeLink clone: proper JeeLinks
also have an extra 16 Mbit flash memory chip. That is not
used by the LaCrosse sketch, so I don't need it, and I left
it out.

