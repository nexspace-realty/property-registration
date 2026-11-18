# Nexspace Realty property registration (owner form)

Digital version of the paper Property Registration sheet, Thai / English.
Live at https://nexspace-realty.github.io/property-registration/

Optional link parameters to pre-fill: `?project=Romm%20Convent&unit=504&type=condo&for=sale,rent&agent=NAME&lang=th`

Submissions (with a signed PDF) go to the same Google Apps Script receiver as the enquiry form
(`nexspace-realty/enquiry/apps-script/Code.gs`), sent with `form: "owner"` so they land in the
"Owner Listings" tab once that script is redeployed. Page is `noindex`, so it won't appear in search.
