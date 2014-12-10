FORMAT: 1A

# CMS Read
Provides read-only access to the contents of Wuaki.

# Group Type definitions

# Device types [/device_types]

## GET

Returns all the device types ºknown to the system.

+ Response 200 (application/json)

        [{
            name: '',
            id: ''
        }]

# Genres [/genres]

## GET

Returns the genres available for the given market_code.

+ Request (application/json)

        {
            market_code: 'es' // Required
        }

+ Response 200 (application/json)

        [{
            name: '',
            id: ''
        }]

# Subscription plans [/subscription_plans]

## GET

Returns all the subcription plans available.

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es'   // Required
        }

+ Response 200 (application/json)

        [{
            name: '',
            id: ''
        }]

# Group Frontpage

# Frontpage [/frontpage]

Provides everything needed to render the frontpage in a single API call.

## GET

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es'  // Required
        }

+ Response 200 (application/json)

        {
            banners: {
                top: [{
                    artwork_url: '',
                    alt_text: '',
                    href: ''
                }]
            },
            links: {
                footer: [{
                    group_name: '',
                    links: [{
                        title: '',
                        url: ''
                    ]
                }]
            },
            lists: [{
                title: '',
                full_list_url: '',
                contents: [{
                    cover_url: '',
                    content_url: '',
                    price_label: '',
                    normalized_rating: 3,
                    title: ''
                }]
            }],
            marketing_links: [{
                artwork_url: '',
                link_url: '',
                alt_text: ''
            }],
            menus: [{
                title: '',
                menu_url: '',
                sections: [{
                    title: '',
                    links: [{
                        link_url: '',
                        title: ''
                    }]
                }]
            }]
        }
    
# Group Movies

# Movies listing [/movies]

Allows to get movie listings, with options to:

- Filter by genre
- Filter belonging to subcription plan 
- Choose a sorting definition for the results
- Paginate the movies

## GET

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es'   // Required
            genre_name: '',
            sort_type: '' // One of by_publication_date, by_popularity or by_title,
            per_page: 10,
            page: 1,
            subscription_plan_id: 1
        }
        
+ Response 200 (application/json)

        {
            paging: {
                per_page: 10
                current_page: 1,
                pages_count: 10
            },
            movies: [{
                id: 3232,
                cover_url: '',
                content_url: '',
                price_label: '',
                rating: 3,
                title: ''
            }]
        }

# Movie details [/movies/{movie_id}]

Returns the details for a movie in a given market and device

## GET

+ Params
    + movie_id (integer) The movie id

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es'   // Required
        }

+ Response 200 (application/json)

        {
            id: {movie_id}
            title: '',
            cover_url: '',
            original_title: '',
            year: '',
            genres: [{
                title: '',
                url: ''
            },
            plot: '',
            cast: [{
                name: '',
                url: ''
            }],
            parental_rating: 12,
            languages: [],
            audio_qualities: [],
            wuaki_rating: {
                normalized_rating: 4,
                ratings_countt: 23
            }
            ratings: [{
                provider_name: '',
                url: '',
                normalized_rating: '',
                raw_rating: 3,
                max_raw_rating: 5
            }],
            related_contents: [{
                    cover_url: '',
                    content_url: '',
                    price_label: '',
                    normalized_rating: 3,
                    title: ''
            }]
        }
        
# Group Tv shows

# TvShow listing [/tv_shows]

## GET

Returns a paged listing of Tv Shows for a given market and device.

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es',  // Required
            per_page: 10,
            page: 1,
        }

+ Response 200 (application/json)

        {
            paging: {
                per_page: 10
                current_page: 1,
                pages_count: 10
            },
            tv_shows: [{
                id: 1231,
                cover_url: '',
                content_url: '',
                label: '',
                title: ''
            }]
        }

# TvShow details [/tv_shows/{tv_show_id}]

## GET

+ Parameters
    + tv_show_id (integer) The tv show id
    
+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es'   // Required
        }

+ Response 200 (application/json)

        {
            id: {tv_show_id}
            title: '',
            seasons: [{
                cover_url: '',
                title: 'Season 1',
                plot: '',
                wuaki_rating: {
                   normalized_rating: 4,
                    ratings_countt: 23
                },
                episodes: [{
                    title: '',
                    url: '',
                    duration_label: ''
                }]
            }]
        }

# Group Lists

# List contents [/list/{list_id}]

## GET

Gets a list of mixed contents (Movies and TvShows)

+ Request (application/json)

        {
            device_type: 'web', // Required
            market_code: 'es',  // Required
            per_page: 10,
            page: 1,
        }

+ Response 200 (application/json)

        {
            paging: {
                per_page: 10
                current_page: 1,
                pages_count: 10
            },
            contents: [{
                cover_url: '',
                content_url: '',
                label: '',
                title: ''
            }]
        }
