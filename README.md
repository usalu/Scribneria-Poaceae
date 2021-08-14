# Scribneria-Poaceae
A conglomerate of open-source Grasshopper script components. The goal of Scibneria is to gather script components to potentially create bundled plugins later. Every script is work in progress. This is part of the [Poaceae] project.

## Why script components?
Versioning and collaborating is something quite difficult in Grasshopper. To be able to work on the same definition requires a lot of communication. One reason for that is that the components store only a link to the actual plugin that does the calculation. Seeing it under the aspect of the file size this is very efficient way of storing definitions. From the developers side it also gives a bunch of advantages. Improvements will even run backward compatible on existing definitions. When it comes to collaborating this way of storing definitions aggravate things a lot. Therefore all plugins in [Poaceae] are pure script components saved as user objects. The advantage of script components is that the code is stored locally. Therefore you can share the component with people who have this plugin not installed. Another big advantage is transparency. If someone wants to modify the code or understand he can just check it. This is only possible due to the open-source access of all components. This way has one major backside. If there is a mistake in the component you will have to change every instance manually

## Organization
Scripts are organized in categories that describe the general purpose of the script. The categories follow the existing ones from Grasshopper if possible.

## Contributing
If you have script components that you want to share with the world feel free to send a pull request and we will be happy to include it into the pool. Most people who use the script component will probably not know code. Therefore it is necessary that all the components are well described and all inputs and outputs have an understandable name and a precise description. [Here] you can find templates for C# and Python script components. Furthermore we have made a [checklist] with questions that we always ask ourselves before publishing a component. Besides that I wrote [6 guidelines] that I use to write script components. Maybe it helps you!

## License
This project is licensed under the GNU Lesser General Public License v3.0.

[Poaceae]: https://github.com/usaluz/Poaceae "Poaceae repository"
[Ueli]: poaceae4rhino@outlook.com "Email Poaceae"
[6 guidelines]: https://github.com/usaluz/Scribneria-Poaceae/blob/master/docs/GuidelinesWrittingGrasshoperScriptComponent.md "Guidelines for script components"


