# Notes

"Valuation changes" section has been added. New colours for positive change have been added to `theme/index` and new styled components added to `property-details/style`

As you can see from commented-out code in `property-details/index` I began work on requesting data from API as instructed, but encountered console errors and ran out of time with it.

The hierarchy of components AccountSection -> RowContainer -> AccountList -> AccountListItem -> InfoText etc. is confusing to look at, and components are poorly named. It's not immediately evident what purpose everything serves, and a component name such as InfoText suggests a styled paragraph or span rather than a div. Given more time I would rename these for more clarity.

Some more thought could be given to the styling, e.g. there are two different border radii here -- could there be more consistency? Aside from the new Valuation Changes section and Edit button, there is little colour. Could there be more? Currency amounts are also shown in two different ways, with/without decimals -- consistency?

## Getting Started

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3333](http://localhost:3333) with your browser to see the result.
