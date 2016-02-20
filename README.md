# d-meta-tag

Derby component to render server-side and client-side meta tags

## Installation

    npm install d-meta-tag --save

## Usage

Include the component:

    app.component(require('d-meta-tag'));

Render meta-tags on the server inside the `head` element:

    <head>
      <d-meta-tag name="description" content="..." render />
    </head>

Dynamically update meta-tags on the client inside the `body` element:

    <body>
      <d-meta-tag name="description" content="..." />
    </body>
