For responsive:

<style>
        /* on mobile browsers, I set a width of 100% */
        table.mceLayout, textarea.tinyMCE {
            width: 100% !important;
        }
        
        /* on large screens, I use a different layout, so 600px are sufficient */
        @media only screen and (min-width: 600px) {
            table.mceLayout, textarea.richEditor {
               width: 600px !important;
            }
        }
    </style>
