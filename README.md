# houzz-scraper

# About Extract Houzz project data scraper

Houzz, a popular platform for home design and remodeling ideas, does not offer a dedicated API for extracting comprehensive project details. Extracting project data from Houzz typically required coding knowledge and API integration.

Luckily, there's a solution available called Apify, a web scraping and automation platform that makes extracting project data from Houzz hassle-free, even without coding. Apify simplifies the process of gathering data from websites.

With the assistance of an Apify script, users can effortlessly retrieve project information from Houzz. The script navigates through Houzz's website, locates the relevant project data, and extracts it for further use. This eliminates the need for users to manually browse through Houzz or write custom code for data retrieval.

The extracted project data can be downloaded in various formats, including CSV (Comma-Separated Values), JSON (JavaScript Object Notation), or Excel. These formats enable easy analysis and manipulation of the project information. Moreover, the extracted data can be integrated into custom workflows, allowing users to incorporate the information into their own systems or processes.

Apify offers a user-friendly interface that enables users to configure and run the script without extensive programming skills. By automating the data extraction process, Apify streamlines the task of retrieving the latest project details from Houzz, making it accessible to a wider range of users.

## Output
```python
 {
    "userId": 111882,
    "professionalId": 18124,
    "formattedAddress": "<span itemprop=\"streetAddress\">1000 South Winchester Blvd.</span><br/><span itemprop=\"addressLocality\">San Jose</span>, <span itemprop=\"addressRegion\">CA</span> <span itemprop=\"postalCode\">95128</span>",
    "formattedPhone": "(831) 292-3471",
    "aboutMe": "19x \"BEST OF HOUZZ\" Winner!\r\n\r\nStudio S Squared Architecture, Inc. was founded in 1996, on the belief that client involvement and a positive relationship is the key to a successful project.  We are committed to a team-oriented approach in all phases of the design process. We believe in the value of collaboration within our office, with our consultant team, the building contractor, and most importantly, with our clients.\r\n\r\nWhen you hire Studio S Squared Architecture, you partner with a diverse, dynamic team of architects and interior designers who will help guide you through the entire design process, from site selection all the way through move in day! We consistently deliver outstanding design that makes the most of your budget—along with innovative ideas that transform your space into something truly extraordinary.\r\n\r\nOur practical experience covers the entire spectrum of styles and scopes of work ranging from modest renovations to large new buildings.  The common thread in our work is the belief that architecture can lift the spirit, and that great relationships make great design possible.\r\n\r\nGreat design involves more than using our expertise to navigate governmental approvals. Clients look to us to take their ideas and elevate them into a design uniquely tailored to their site, program, and financial needs. We work to keep the lines of communication with clients open at all times to ensure that we can craft a building that is uniquely their own. With this approach, it is possible to create a “signature” building with every project we design.\r\n\r\nOur firm is committed to conservation and wise use of our natural resources, and minimizing our projects' impact on both the built and unbuilt environment. We also commit a percentage of our billable hours every year to local non-profits in need of pro bono or reduced-cost architectural services.",
    "proTypeDisplayName": "Architects & Building Designers",
    "location": "San Jose, CA",
    "proType": 1,
    "address": "1000 South Winchester Blvd. ",
    "city": "San Jose",
    "state": "CA",
    "zip": "95128",
    "country": "US",
    "seoHint": {
      "paths": {
        "ViewProfessional": {
          "command": "professionals",
          "extraSlugs": "architects-and-building-designers",
          "titleSlug": "studio-s-squared-architecture-inc",
          "seoPageType": "pfvwus",
          "indexing": true
        }
      }
    },
    "highlightBadges": {
      "meritProfileBadges": [
        {
          "id": 4000,
          "title": "Hired on Houzz",
          "shortTitle": "Hired on Houzz",
          "titleWithValue": "4 Hires on Houzz",
          "description": "The number of homeowners who contacted a pro through Houzz and then hired that pro for a project.",
          "selfDescription": "The number of homeowners who contacted a pro through Houzz and then hired that pro for a project.",
          "type": 11,
          "cta": "",
          "modified": "2022-08-26 11:31:02",
          "awardedOnDate": "1661538662",
          "imageNames": [
            "handshake"
          ],
          "value": 4
        }
      ],
      "profileBadges": [
        {
          "id": 1000,
          "title": "Best of Houzz winner",
          "shortTitle": "Best of Houzz winner",
          "titleWithValue": "Best of Houzz winner",
          "description": "The annual Best of Houzz Award recognizes the top-rated & top-contributing home pros around the world.",
          "selfDescription": "The annual Best of Houzz Award recognizes the top-rated & top-contributing home pros around the world.",
          "type": 16,
          "cta": "",
          "modified": "2022-02-11 16:52:00",
          "awardedOnDate": "1644627120",
          "imageNames": [
            "badge1"
          ]
        },
        {
          "id": 1006,
          "title": "Eco-friendly",
          "shortTitle": "Eco-friendly",
          "titleWithValue": "Eco-friendly",
          "description": "This business is environmentally conscious and supports sustainable practices.",
          "selfDescription": "This business is environmentally conscious and supports sustainable practices.",
          "type": 16,
          "cta": "",
          "modified": "2022-02-11 16:52:01",
          "awardedOnDate": "1644627121",
          "imageNames": [
            "leaf"
          ]
        },
        {
          "id": 1009,
          "title": "Online consultation",
          "shortTitle": "Online consultation",
          "titleWithValue": "Online consultation",
          "description": "This business offers an initial online consultation with no obligation.",
          "selfDescription": "This business offers an initial online consultation with no obligation.",
          "type": 16,
          "cta": "",
          "modified": "2022-02-11 16:52:02",
          "awardedOnDate": "1644627122",
          "imageNames": [
            "sb_ellipsis_overlap"
          ]
        }
      ]
    },
    "isSponsoredResult": false,
    "isVideoConsultationEnabled": false,
    "budgetLevels": [
      "1v3",
      "1v4"
    ],
    "proDirectoryCardSetting": {
      "showHighlightVideo": true,
      "budgetLevels": [
        "1v3",
        "1v4"
      ],
      "badgeSettings": [
        {
          "badgeOptionId": 4000,
          "presentableMinValue": 1
        },
        {
          "badgeOptionId": 4001,
          "presentableMinValue": 1
        }
      ],
      "badgeSettingsMap": {
        "4000": {
          "presentableMinValue": 1
        },
        "4001": {
          "presentableMinValue": 1
        }
      }
    },
    "webProTrackInfo": {
      "profileClk": {
        "method": "GET",
        "protocol": "https",
        "domain": "www.houzz.com",
        "path": "/hsc/aetrk/k=HBkcFQYVGhaQlYvLDBgKMjE0MjA0NzQ2MSgkNjNjM2VjMmMtMTFmMS00YzBlLWJlZjItN2MxYTU5ZmY3MWU2EhgONTQuMTk4LjIyNi4xMzQYGC9VUy9WQS81MTEvQXNoYnVybi8yMDE0ORk4BzEwMDAwMDAHMTAwMDA0NQI1ORUAaAMxMDFYBjExMTg4MhUEFQQVAjh7aHR0cHM6Ly93d3cuaG91enouY29tL3Byb2Zlc3Npb25hbHMvYXJjaGl0ZWN0cy1hbmQtYnVpbGRpbmctZGVzaWduZXJzL3N0dWRpby1zLXNxdWFyZWQtYXJjaGl0ZWN0dXJlLWluYy1wZnZ3dXMtcGZ-NzIxNTEzMTk4CGA_YzItdGhyaWZ0LW1haW4tMnBrZ3JlbGVhc2UyMDIzMDcxMzA4MjExNjE5MzYzMjktNmQ4YjQ2YmJkNjI0dGdmGCRhMzQzMzYyZi1lZDIzLTQ2NTctYWQyMy0zZTczNjAzODI0YTnCAAAA"
      }
    },
    "mostRecentReview": {
      "body": "We worked with Eugene, Jose, and the team to architect our 3200 sq. ft. modern dream home in Redwood City. We couldn't be happier with the end results and the contractor they referred to us (Greenberg Construction). The design of the house, permitting process, and transition into construction was seamless. The exterior architecture of the home was absolutely stunning - Jose is a visionary. Although we loved the interior design in SketchUp, many of the elements weren't reflected in the construction documents (sunken living room, recessed blinds) and the finishes came in well over the budget we specified, so we had to redo the interior design during construction. However, with that one caveat, we are very happy with the end result!",
      "user": {
        "userName": "timju",
        "displayName": "Tim J"
      }
    },
    "hasVerifiedLicense": true,
    "hasVerifiedKyc": false,
    "isInactivePro": false,
    "numReviews": 100,
    "reviewRating": 50,
    "featuredReview": {
      "text": "Eugene was attentive to our requests, understood our vision and respectful of our budget. We went back and forth many, many times over a year and never once did he make me feel that we were wasting his time. The end design was beautiful ",
      "rawReview": {
        "user": {
          "userName": "amyhsiao",
          "displayName": "amyhsiao"
        }
      }
    },
    "proSkuId": 4
  }

  ```



  ## ✨ Maximize Efficiency: Extract Houzz project data with Apify API ✨


The Apify API empowers you with programmatic access to the comprehensive Apify platform. With RESTful HTTP endpoints at your disposal, you can effortlessly manage, schedule, and execute Apify actors. Additionally, the API facilitates seamless access to datasets, performance monitoring, result retrieval, version creation, updates, and much more.

Leverage the apify-client NPM package to tap into the API using Node.js, or employ the apify-client PyPI package for Python integration.

For comprehensive information, explore the Apify API reference [documentation](https://docs.apify.com/api/v2), or simply click on the API tab to explore insightful code examples.


## 💬 Feedback 💬

If you have any technical feedback or encountered a bug while using the Extract Houzz project data, please create an issue on the actor's dedicated ["Issues"](https://console.apify.com/actors/PmxIAXfwo0gUUNdG4/issues) tab in the Apify Console. We value your input and appreciate your help in improving our services.
