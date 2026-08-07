# SO2 L02 - ENTITIES, INSTANCES, ATTRIBUTES, AND IDENTIFIERS
<p><br></p>
<ul>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><strong><span style="font-size:11pt;font-family:Arial,sans-serif;">Entity&nbsp;</span></strong><span style="font-size:11pt;font-family:Arial,sans-serif;">- &ldquo;Something&rdquo; of significance to the business about which data must be known</span></p>
        <ul>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">A name for a set of similar things that you can list.&nbsp;</span></p>
            </li>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Usually a noun</span></p>
            </li>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Examples: objects, events, people</span></p>
            </li>
        </ul>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><strong><span style="font-size:11pt;font-family:Arial,sans-serif;">Instance&nbsp;</span></strong><span style="font-size:11pt;font-family:Arial,sans-serif;">- An instance is a single occurrence of an entity.</span></p>
        <ul>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">A Dalmatian, a Siamese cat, a cow and a pig are instances of ANIMAL entity.</span></p>
            </li>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">A convertible, a sedan and a station wagon are instances of CAR entity.</span></p>
            </li>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Some entities have many instances and some have only a few</span></p>
            </li>
        </ul>
    </li>
</ul>
<img src="./assets/S02-L02/{C989CDA0-5B3A-495B-9888-5FB3931F9F89}.png">

<ul>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><strong><span style="font-size:11pt;font-family:Arial,sans-serif;">Attribute</span></strong><span style="font-size:11pt;font-family:Arial,sans-serif;">&nbsp;- Like an entity, an attribute represents something of significance to the business. An attribute is a specific piece of information that helps: </span></p>
    </li>
    <ul>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Attributes help you distinguish between one instance and another by providing greater detail for the entity.</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Describe an entity</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
            <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Quantify an entity</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
            <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Qualify an entity</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
            <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Classify an entity</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
            <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Specify an entity</span></p>
        </li>
        <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
            <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">An attribute has a single value.</span></p>
        </li>
    </ul>
</ul>
<img src="./assets/S02-L02/{98DFDCC8-105C-4421-A771-80D2C6F1A8C5}.png">
<ul>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Attributes have values. An attribute value can be a number, a character string, a date, an image, a sound, etc. These are called &quot;data types&quot; or &quot;formats.&quot; Every attribute stores one piece of data of one specific data type.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Some attributes (such as age) have values that constantly change. These are called volatile attributes.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Other attributes (such as order date) will rarely change, if ever. These are nonvolatile attributes.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">If given a choice, select the nonvolatile attribute. For example, use birth date instead of age.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Some attributes must contain a value&mdash;these are mandatory attributes. For example: in most businesses that track personal information, name is required.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">Other attributes may either contain a value or be left null&mdash;these are optional attributes. For example: cellphone number is often optional except in mobile or wireless applications.</span></p>
    </li>
    <li style="list-style-type:disc;font-size:11pt;font-family:Arial,sans-serif;">
        <p role="presentation"><strong><span style="font-size:11pt;font-family:Arial,sans-serif;">Identifiers</span></strong><span style="font-size:11pt;font-family:Arial,sans-serif;">&nbsp;- Unique identifier (UID) is either a single attribute or a combination of multiple attributes that distinguishes one from another.</span></p>
        <ul>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">In a classroom, you need to distinguish between one student and another.</span></p>
            </li>
            <li style="list-style-type:circle;font-size:11pt;font-family:Arial,sans-serif;">
                <p role="presentation"><span style="font-size:11pt;font-family:Arial,sans-serif;">When classifying your CD collection, you need to distinguish between one CD and another.</span></p>
            </li>
        </ul>
    </li>
</ul>