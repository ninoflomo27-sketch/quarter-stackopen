### what i asked
The situation: a small business near you — a tailor, a phone-repair shop, a salon, a food
seller, a printing shop — has no web presence at all. You are making the one page that tells
people what they offer.
Use a real business you can name, and real services at plausible prices. Ask them if you can.
Cold recall — before opening any notes. Write down: when do you use <ol> and when
<ul> , and where exactly does a nested list go relative to its <li> ? Then check yourself
against 1c.
Requirements:
At least two <h3> subsections under one of the <h2> s
No skipped levels anywhere
A short paragraph under every heading — real information, not placeholder text
Zero validator errors
Build the outline before you write a word of HTML
Write the headings as a plain indented list on paper first. It takes three minutes and it is the
entire difficulty of this exercise — the HTML is the easy part.
Create services.html
One <h1> with the business name, and a short paragraph saying what they do and where
they are
At least three <h2> sections grouping their services
At least one <ol> and at least one <ul> — and be ready to justify each choice
At least one nested list — a category with items inside it


make it Aura photograpy studio and put the pricing based on the right format there should'nt be any  css or  javascript involved 

### what i got
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aura Photography Studio - Services and Prices</title>
</head>
<body>

    <h1>Aura Photography Studio</h1>

    <p>
        Aura Photography Studio offers portrait photography, event photography,
        and other photography services in The Gambia. We aim to capture
        beautiful moments and create lasting memories for our clients.
    </p>

    <h2>Our Services</h2>

    <p>
        We provide photography services for individuals, families, and special
        occasions at affordable prices.
    </p>

    <h3>Portrait Photography</h3>

    <p>
        We take individual and family portraits for birthdays, personal
        collections, and social media profiles.
    </p>

    <ul>
        <li>Individual portrait session — GMD 300</li>
        <li>Family portrait session — GMD 500</li>
        <li>Birthday portraits — GMD 500</li>
    </ul>

    <h3>Event Photography</h3>

    <p>
        We capture important moments at celebrations and special events.
        Prices depend on the length and size of the event.
    </p>

    <ul>
        <li>Small birthday event — GMD 1,500</li>
        <li>Engagement photography — GMD 2,000</li>
        <li>Wedding photography — from GMD 5,000</li>
    </ul>

    <h2>Photography Packages</h2>

    <p>
        Clients can choose a package based on their photography needs and budget.
    </p>

    <h3>Basic Package</h3>

    <p>
        The Basic Package costs GMD 500 and includes a short portrait session
        with five edited digital photographs.
    </p>

    <h3>Premium Package</h3>

    <p>
        The Premium Package costs GMD 1,000 and includes a longer portrait
        session with ten edited digital photographs.
    </p>

    <h2>Additional Services</h2>

    <p>
        Clients can request extra services to make their photography sessions
        more suitable for their needs.
    </p>

    <ul>
        <li>Photo editing
            <ul>
                <li>Brightness and colour correction</li>
                <li>Background adjustments</li>
                <li>Skin tone correction</li>
            </ul>
        </li>
        <li>Extra edited photograph — GMD 50 per photo</li>
        <li>Printed photograph — price depends on size</li>
    </ul>

    <h2>How to Book</h2>

    <p>
        Follow these steps to arrange a photography session with Aura Photography Studio.
    </p>

    <ol>
        <li>Choose the photography service you need.</li>
        <li>Contact the studio to discuss your preferred date and time.</li>
        <li>Confirm the price and booking details.</li>
        <li>Attend your session or event at the agreed time.</li>
    </ol>

    <h2>Our Opening Hours</h2>

    <p>
        Contact the studio to confirm availability before visiting. Sessions
        outside normal hours may be arranged by appointment.
    </p>

    <ul>
        <li>Monday to Friday: 9:00 AM – 6:00 PM</li>
        <li>Saturday: 10:00 AM – 5:00 PM</li>
        <li>Sunday: By appointment</li>
    </ul>

</body>
</html>
```
### whT I CHANEED
CHAT GBT GIVE ME A RANDON  STUDIO  name and location
so i put   aura production  and my location is kololi

 chat gbt give me had my working days wrong Monday to Friday: 9:00 AM – 6:00 PM Saturday: 10:00 AM – 5:00 PMSunday: By appointment
 Monday to Friday: 9:00 AM – 9:00 PM
        <Saturday: 10:00 AM – 12:00 PM Sunday: By appointment
        so i change the time  Monday to Friday: 9:00 AM – 6:00 PM
        Saturday: 10:00 AM – 5:00 PMSunday: By appointment
        
    

    


