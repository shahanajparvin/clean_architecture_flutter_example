<div align="center">
  <h1>Flutter Clean Architecture Example</h1>
</div>

<h2>Overview</h2>

<p>The project is structured using Clean Architecture principles, which divide the codebase into several layers:</p>

<ul>
  <li><strong>Presentation Layer:</strong> This layer contains UI components, including screens, widgets, and Flutter-specific code.</li>
  <li><strong>Domain Layer:</strong> Here, we define the business logic and use cases of the application. It includes the core business rules and entities.</li>
  <li><strong>Data Layer:</strong> This layer manages data sources, repositories, and data models. It handles data retrieval and storage.</li>
</ul>

<h2>Features</h2>

<ul>
  <li><strong>Clean Separation of Concerns:</strong> Clear separation between layers for better maintainability and testability.</li>
  <li><strong>Dependency Injection:</strong> We use the get_it package for managing dependencies.</li>
  <li><strong>Sample Use Cases:</strong> Includes sample interactions and use cases.</li>
  <li><strong>Organized Project Structure:</strong> A well-organized structure for easy navigation and development.</li>
</ul>

<h2>Getting Started</h2>

<p>Follow these steps to run this project on your local machine:</p>

<ol>
  <li>Clone the repository:</li>
</ol>

<pre>
<code>
git clone https://github.com/shahanajparvin/clean_architecture_flutter_example.git
</code>
</pre>

<ol start="2">
  <li>Navigate to the project directory:</li>
</ol>

<pre>
<code>
cd flutter-clean-architecture-example
</code>
</pre>

<ol start="3">
  <li>Install dependencies:</li>
</ol>

<pre>
<code>
flutter pub get
</code>
</pre>

<ol start="4">
  <li>Run the app:</li>
</ol>

<pre>
<code>
flutter run
</code>
</pre>

<h2>Dependencies</h2>

<p>We use several packages to facilitate Clean Architecture and improve developer productivity, including:</p>

<ul>
  <li><strong>get_it</strong> for dependency injection.</li>
  <li><strong>dio</strong> for making network requests.</li>
  <li><strong>equatable</strong> for value equality.</li>
  <li><strong>bloc</strong> for state management.</li>
</ul>

<p>For the complete list of dependencies, refer to the pubspec.yaml file.</p>

<h2>Contributing</h2>

<p>If you would like to contribute to this project or have suggestions for improvements, please feel free to open an issue or submit a pull request. We welcome and appreciate your contributions!</p>

<p>This project is licensed under the MIT License.</p>


