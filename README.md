<h1>Changelog API (Node.js)</h1>
<p>This project implements a Node.js API for managing product changelogs, updates, new features, and can also function as a personal timeline. It utilizes a relational database and leverages JWT (JSON Web Token) based authentication for secure access.</p>

<h2>Features</h2>
<ul style="list-style: none; padding: 0;">
<li style="margin-bottom: 0.25rem;">CRUD operations on products and updates.</li>
<li style="margin-bottom: 0.25rem;">User signup and signin with JWT-based authentication.</li>
<li style="margin-bottom: 0.25rem;">Designed for relational database.</li>
</ul>

<h2>Getting Started</h2>
<ol>
<li>Clone the repo, install dependencies (<code>npm install</code>).</li>
<li>Set environment variables (<code>.env</code> not included):
<ul style="padding: 0;">
<li style="margin-bottom: 0.25rem;"><code>DATABASE_URL</code>: Database connection URL.</li>
<li style="margin-bottom: 0.25rem;"><code>JWT_SECRET</code>: Secret key for JWT generation.</li>
</ul>
</li>
<li>Implement database migrations.</li>
<li>Start the server (<code>npm start</code>).</li>
</ol>

<h2>API Endpoints</h2>
<ul style="list-style: none; padding: 0;">
<li style="margin-bottom: 0.25rem;">Products (CRUD): <code>/products</code> (<code>/:id</code>)</li>
<li style="margin-bottom: 0.25rem;">Updates (CRUD): <code>/updates</code> (<code>/:id</code>)</li>
<li style="margin-bottom: 0.25rem;">Users (Signup, Signin): <code>/users/signup</code>, <code>/users/signin</code></li>
</ul>
<p>Authentication: JWT token required in Authorization header (Bearer &lt;token&gt;).</p>

<p>Full details and usage in code.</p>

<h2>Testing and Deployment</h2>
<ul style="padding: 0;">
<li style="margin-bottom: 0.25rem;">Unit/integration tests encouraged (Jest recommended).</li>
<li style="margin-bottom: 0.25rem;">Deployable to production environments (Heroku, AWS).</li>
</ul>
<!-- <h2>MIT License</h2>
<p>This project is licensed under the MIT License. See https://opensource.org/license/mit for details.</p> -->
