# API diff: SkiaSharp.Views.Forms.dll

## SkiaSharp.Views.Forms.dll

### Namespace SkiaSharp.Views.Forms

#### Type Changed: SkiaSharp.Views.Forms.SKGLView

Added interface:

```csharp
ISKGLViewController
```


#### New Type: SkiaSharp.Views.Forms.ISKGLViewController

```csharp
public interface ISKGLViewController : Xamarin.Forms.IElementController, Xamarin.Forms.IViewController, Xamarin.Forms.IVisualElementController {
	// events
	public event System.EventHandler<SkiaSharp.Views.Forms.GetPropertyValueEventArgs<SkiaSharp.SKSize>> GetCanvasSize;
	public event System.EventHandler<SkiaSharp.Views.Forms.GetPropertyValueEventArgs<SkiaSharp.GRContext>> GetGRContext;
	public event System.EventHandler SurfaceInvalidated;
	// methods
	public virtual void OnPaintSurface (SKPaintGLSurfaceEventArgs e);
	public virtual void OnTouch (SKTouchEventArgs e);
}
```


