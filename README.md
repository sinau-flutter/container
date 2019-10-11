# container_app

All about Container Widget

## Getting Started

Container only have one child. That means Container can only have one `widget` :

```dart
body: Container(
          color: Colors.teal,
          padding: EdgeInsets.all(20),
          child: Container(
            margin: EdgeInsets.all(30),
            decoration: BoxDecoration(
                borderRadius: BorderRadius.circular(20),
                gradient: LinearGradient(
                    begin: Alignment.topLeft,
                    end: Alignment.bottomRight,
                    colors: <Color>[Colors.amber, Colors.white70])),
          ),
        ),
```

## Properties

1. alignment → AlignmentGeometry
   Align the child within the container. [...]

2. child → Widget
   The child contained by the container. [...]

3. constraints → BoxConstraints
   Additional constraints to apply to the child. [...]

4. decoration → Decoration
   The decoration to paint behind the child. [...]

5. foregroundDecoration → Decoration
   The decoration to paint in front of the child.

6. margin → EdgeInsetsGeometry
   Empty space to surround the decoration and child.

7. padding → EdgeInsetsGeometry
   Empty space to inscribe inside the decoration. The child, if any, is placed inside this padding. [...]

8. transform → Matrix4
   The transformation matrix to apply before painting the container.

9. hashCode → int
   The hash code for this object. [...]

10. key → Key
    Controls how one widget replaces another widget in the tree. [...]

11. runtimeType → Type
    A representation of the runtime type of the object.

You can see the full example from [here](https://api.flutter.dev/flutter/widgets/Container-class.html)
